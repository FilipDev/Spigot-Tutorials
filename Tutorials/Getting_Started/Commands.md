##Commands
Commands are usually the most desirable, and commonly feature used in a Bukkit plugin.

###The onCommand() Method
The onCommand() method is called whenever a command registered by your plugin is executed. This method is in the JavaPlugin class, and the CommandExecutor interface. You are meant to override this method and fill it with your own implementation. We will first be going over commands in your main class, and then commands in seperate classes.

####Method Header
The method header for the onCommand() method looks like this

	public boolean onCommand(CommandSender sender, Command command, String label, String[] args)
	
The return type, boolean, represents whether the command was a success, or not. The CommandSender represents the person executing the command; it is either the console, or a player. The Command instance contains information about the command that was executed. You can view the specific methods in the class below in the Sources section. The String is the command alias that was used and the String array are the arguments of the command. The arguments of '/teleport Player 100 60 100' would look like ["Player", "10", "60", "100"], but the actual command would be 'teleport.'

###Your First Command
To create your first command you are going to have to register it in you plugin.yml file; however, we will not be going over this. The second step is overriding the onCommand() method and adding your own implementation. Here is an example.

	public final class MyPlugin extends JavaPlugin {
	
		@Override
		public boolean onCommand(CommandSender sender, Command command, String label, String[] args) {
			if(command.getName().equalsIgnoreCase("hello")) {
				sender.sendMessage("world!");
				return true;
			}
			return false;
		}
	}
	
Since you can register multiple commands and this method is invoked whenever one of those commands is executed, we must check whether the command that was executing is the one we want. In this case, we are checking if the command is /hello. We ignore the case of the characters by using equalsIgnoreCase(). When the command /hello is executed the user who executed it will get the message "world!" After sending the message, we return true which tells Bukkit that the method was a success. If the method were to have returned false, the user would have got a message explaining the usage of the plugin. You define this message when registering the plugin.

###Multiple Classes
When creating commands you have two options. Either you can handle them in your main class, or in a seperate class. This seperate class must implement CommandExecutor. This interface has a single method, onCommand(). This method is exactly the same as it is in the JavaPlugin class. Here is an example using the /hello command we created earlier.

	public class HelloCommand implements CommandExecutor {
	
		@Override
		public boolean onCommand(CommandSender sender, Command command, String label, String[] args) {
			sender.sendMessage("world!");
			return true;
		}
	}
	
In this example we don't need to check whether the command is /hello because this method is only going to be invoked when /hello is executed. This class is set up correctly; however, the command will not do anything because we have yet to implement this with our main class. You can do that by settings the CommandExecutor for the command /hello when the plugin is enabled. You can do that in your main class like this.

	public final class MyPlugin extends JavaPlugin {
	
		@Override
		public void onEnable() {
			this.getCommand("hello").setExecutor(new HelloCommand());
		}
	}

Essentially, the onCommand() method inside your CommandExecutor is invoked whenever a player, or the console executes the /hello command. If you want to use the same class for multiple commands, you have the check the name of the command as we did in the first example.

###Handling Arguments
Sometimes you need a command to have multiple arguments such using '/hello friend' instead of just /hello. You can easily do this by using the String array passed to your onCommand() method. Here is an example.

	public final class MyPlugin extends JavaPlugin {
	
		@Override
		public boolean onCommand(CommandSender sender, Command command, String label, String[] args) {
			if(command.getName().equalsIgnoreCase("hello")) {
				if(args.length == 1 && args[0].equalsIgnoreCase("friend")) {
					sender.sendMessage("Hello!");
				}
			}
			return false;
		}
	}

First we check if there is one argument, and if there is, then we check whether that argument equals 'friend.' If both are successful we send the user the message, 'Hello!'

###Sources
- [Javadocs: String](http://docs.oracle.com/javase/7/docs/api/java/lang/String.html)
- [Javadocs: JavaPlugin](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/plugin/java/JavaPlugin.html)
- [Javadocs: CommandSender](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/command/CommandSender.html)
- [Javadocs: Command](https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/command/Command.html)
- [Javadocs: CommandExecutor](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/command/CommandExecutor.html)
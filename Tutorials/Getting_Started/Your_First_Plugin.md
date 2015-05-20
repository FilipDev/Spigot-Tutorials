##Your First Plugin
This tutorial will teach you how to write your first plugin. We will not be going over how to setup your workspace, and you should assume that all classes used are being imported. To setup your project you can refer to [this](http://wiki.bukkit.org/Plugin_Tutorial) official tutorial.

###The Main Class
The class that controls most of your plugin is commonly referred to as your main class. The main class extends Bukkit's JavaPlugin class. Here is an empty, example main class.

	public final class MyPlugin extends JavaPlugin {
	
	}
	
We make this class final because only one instance of your main class can exist. This instance is created by Bukkit and instantitaing your main class, or a subclass of your main class will result in an IllegalArgumentException.
	
###onEnable() and onDisable()
Almost every plugin uses these methods. The onEnable() method is essentially used in replacement of the main method of traditional Java programs. This method is in the JavaPlugin class and is invoked when your plugin is enabled. In contrast, the onDisable() method is invoked when your plugin is disabled.

###Logging To The Console
Plugins can log messages to the console as well as the log file. Each plugin has a logger specific to that plugin. Here is an example using everything we have learned in this tutorial.

	public final class MyPlugin extends JavaPlugin {
	
		@Override
		public void onEnable() {
			this.getLogger().info("Enabled");
		}
		
		@Override
		public void onDisable() {
			this.getLogger().info("Disabled");
		}
	}
	
You can probably tell, but we are invoking the getLogger() method. This method returns your plugin's Logger which is used to log messages. You can view all of the methods in this class below in the sources section. This example is extremely basic. All it will do is log 'Enabled' when the plugin is enabled, and 'Disabled' when the plugin is disabled.

####Sources
- [Javadocs: Logger](http://docs.oracle.com/javase/7/docs/api/java/util/logging/Logger.html)
- [Javadocs: JavaPlugin](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/plugin/java/JavaPlugin.html)
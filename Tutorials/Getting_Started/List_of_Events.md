##List of Events
This list assumes you are using the latest version of Spigot as it has certain events that Bukkit does not.

###Player Events
- **[AsyncPlayerChatEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/AsyncPlayerChatEvent.html)**: Called when a player chats
- **[AsyncPlayerPreLoginEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/AsyncPlayerPreLoginEvent.html)**: Called when a player attempts to login
- **[PlayerAchievementAwardedEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerAchievementAwardedEvent.html)**: Called when a player earns an achievement
- **[PlayerAnimationEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerAnimationEvent.html)**: Called when an animation is triggered
- **[PlayerArmorStandManipulateEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerArmorStandManipulateEvent.html)**: Called when a player interacts with an armor stand and will either swap, retrieve or place an item
- **[PlayerBedEnterEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerBedEnterEvent.html)**: This event is fired when the player is almost about to enter the bed
- **[PlayerBedLeaveEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerBedLeaveEvent.html)**: This event is fired when the player is leaving a bed
- **[PlayerBucketEmptyEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerBucketEmptyEvent.html)**: Called when a player empties a bucket
- **[PlayerBucketEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerBucketEvent.html)**: Called when a player interacts with a bucket
- **[PlayerBucketFillEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerBucketFillEvent.html)**: Called when a player fills a bucket
- **[PlayerChangedWorldEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerChangedWorldEvent.html)**: Called when a player switches to another world.
- **[PlayerChannelEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerChannelEvent.html)**: Called when a player registers, or unregisters a plugin channel
- **[PlayerChatEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerChatEvent.html)**: Called when a player chats
- **[PlayerChatTabCompleteEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerChatTabCompleteEvent.html)**: Called when a player attempts to tab-complete a chat message
- **[PlayerCommandPreprocessEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerCommandPreprocessEvent.html)**: This event is called whenever a player runs a command
- **[PlayerDeathEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/PlayerDeathEvent.html)**: Called when a player dies
- **[PlayerDropItemEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerDropItemEvent.html)**: Thrown when a player drops an item from their inventory
- **[PlayerEditBookEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerEditBookEvent.html)**: Called when a player edits or signs a book and quill item
- **[PlayerEggThrowEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerEggThrowEvent.html)**: Called when a player throws an egg
- **[PlayerExpChangeEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerExpChangeEvent.html)**: Called when a players experience changes naturally
- **[PlayerFishEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerFishEvent.html)**: Called when a player is fishing
- **[PlayerGameModeChangeEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerGameModeChangeEvent.html)**: Called when the gamemode of the player is changed
- **[PlayerInteractAtEntityEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerInteractAtEntityEvent.html)**: Called when a player right clicks an entity with a location on the entity that was clicked
- **[PlayerInteractEntityEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerInteractEntityEvent.html)**: Called when a player right clicks an entity
- **[PlayerInteractEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerInteractEvent.html)**: Called when a player right clicks an entity
- **[PlayerItemBreakEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerItemBreakEvent.html)**: Called when a player's item breaks
- **[PlayerItemConsumeEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerItemConsumeEvent.html)**: Called when a player is finishing consuming an item
- **[PlayerItemDamageEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerItemDamageEvent.html)**: Called when a player's item is damaged
- **[PlayerItemHeldEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerItemHeldEvent.html)**: Called when a player changes their currently held item
- **[PlayerJoinEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerJoinEvent.html)**: Called when a player joins the server
- **[PlayerKickEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerKickEvent.html)**: Called when a player gets kicked from the server
- **[PlayerLeashEntityEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/PlayerLeashEntityEvent.html)**: Called immediately prior to a creature being leashed by a player
- **[PlayerLevelChangeEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerLevelChangeEvent.html)**: Called when a player's level changes
- **[PlayerLoginEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerLoginEvent.html)**: Called when a player logs into the server
- **[PlayerMoveEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerMoveEvent.html)**: Called when a player moves
- **[PlayerPickupItemEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerPickupItemEvent.html)**: Called when a player picks an item up from the ground
- **[PlayerPortalEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerPortalEvent.html)**: Called when a player is about to teleport because they are in contact with a portal
- **[PlayerPreLoginEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerPreLoginEvent.html)**: Called when a player attempts to login
- **[PlayerQuitEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerQuitEvent.html)**: Called when a player leaves the server
- **[PlayerRegisterChannelEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerRegisterChannelEvent.html)**: Called immediately after a player registers for a plugin channel
- **[PlayerRespawnEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerRespawnEvent.html)**: Called when a player respawns
- **[PlayerShearEntityEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerShearEntityEvent.html)**: Called when a player shears an entity
- **[PlayerStatisticIncrementEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerStatisticIncrementEvent.html)**: Called when a player statistic is incremented
- **[PlayerTeleportEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerTeleportEvent.html)**: Called when a player teleports
- **[PlayerToggleFlightEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerToggleFlightEvent.html)**: Called when a player toggles their flying state
- **[PlayerToggleSneakEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerToggleSneakEvent.html)**: Called when a player toggles their sneaking state
- **[PlayerToggleSprintEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerToggleSprintEvent.html)**: Called when a player toggles their sprinting state
- **[PlayerUnleashEntityEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerUnleashEntityEvent.html)**: Called prior to an entity being unleashed due to a player's action
- **[PlayerUnregisterChannelEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerUnregisterChannelEvent.html)**: Called immediately after a player unregisters for a plugin channel
- **[PlayerVelocityEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/player/PlayerVelocityEvent.html)**: Called when the velocity of a player changes

###Entity Events
- **[CreatureSpawnEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/CreatureSpawnEvent.html)**: Called when a creature is spawned into a world
- **[CreeperPowerEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/CreeperPowerEvent.html)**: Called when a creeper is struck by lightning
- **[EntityBreakDoorEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityBreakDoorEvent.html)**: Called when an entity breaks a door
- **[EntityChangeBlockEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityChangeBlockEvent.html)**: Called when any entity, excluding players, changes a block
- **[EntityCombustByBlockEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityCombustByBlockEvent.html)**: Called when a block causes an entity to combust.
- **[EntityCombustByEntityEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityCombustByEntityEvent.html)**: Called when an entity causes another entity to combust
- **[EntityCombustEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityCombustEvent.html)**: Called when an entity combusts
- **[EntityCreatePortalEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityCreatePortalEvent.html)**: Thrown when a living entity creates a portal in a world
- **[EntityDamageByBlockEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityDamageByBlockEvent.html)**: Called when an entity is damaged by a block
- **[EntityDamageByEntityEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityDamageByEntityEvent.html)**: Called when an entity is damaged by an entity
- **[EntityDamageEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityDamageEvent.html)**: Called when an entity is damaged
- **[EntityDeathEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityDeathEvent.html)**: Called when a living entity dies
- **[EntityExplodeEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityExplodeEvent.html)**: Called when an entity explodes
- **[EntityInteractEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityInteractEvent.html)**: Called when an entity interacts with an object
- **[EntityPortalEnterEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityPortalEnterEvent.html)**: Called when an entity comes into contact with a portal
- **[EntityPortalEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityPortalEvent.html)**: Called when a non-player entity is about to teleport because it is in contact with a portal
- **[EntityPortalExitEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityPortalExitEvent.html)**: Called before an entity exits a portal.
- **[EntityRegainHealthEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityRegainHealthEvent.html)**: Called when an entity regains health
- **[EntityShootBowEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityShootBowEvent.html)**: Called when a LivingEntity shoots a bow firing an arrow
- **[EntitySpawnEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntitySpawnEvent.html)**: Called when an entity is spawned into a world
- **[EntityTameEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityTameEvent.html)**: Called when a living entity is tamed
- **[EntityTargetEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityTargetEvent.html)**: Called when a creature targets or untargets another entity
- **[EntityTargetLivingEntityEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityTargetLivingEntityEvent.html)**: Called when an entity targets a living entity
- **[EntityTeleportEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityTeleportEvent.html)**: Called when a non-player entity tries to teleport from one location to another
- **[EntityUnleashEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/EntityUnleashEvent.html)**: Called immediately prior to an entity being unleashed.
- **[ExpBottleEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/ExpBottleEvent.html)**: Called when an experience bottle hits and releases experience.
- **[ExplosionPrimeEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/ExplosionPrimeEvent.html)**: Called when an entity has made a decision to explode
- **[FoodLevelChangeEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/FoodLevelChangeEvent.html)**: Called when a human entity's food level changes
- **[HorseJumpEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/HorseJumpEvent.html)**: Called when a horse jumps
- **[ItemDespawnEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/ItemDespawnEvent.html)**: Called when a item is removed from the world because it has existed for five minutes
- **[ItemSpawnEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/ItemSpawnEvent.html)**: Called when an item is spawned into a world
- **[PigZapEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/PigZapEvent.html)**: Called when a pig is struck by lightning
- **[PotionSplashEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/PotionSplashEvent.html)**: Called when a splash potion hits an area
- **[ProjectileHitEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/ProjectileHitEvent.html)**: Called when a projectile hits an object
- **[ProjectileLaunchEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/ProjectileLaunchEvent.html)**: Called when a projectile is launched
- **[SheepDyeWoolEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/SheepDyeWoolEvent.html)**: Called when a sheep's wool is dyed
- **[SheepRegrowWoolEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/SheepRegrowWoolEvent.html)**: Called when a sheep regrows its wool
- **[SlimeSplitEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/SlimeSplitEvent.html)**: Called when a slime splits into smaller slimes upon death
- **[SpawnerSpawnEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/entity/SpawnerSpawnEvent.html)**: Called when an entity is spawned into a world by a spawner

###Block Events
- **[BlockBreakEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockBreakEvent.html)**: Called when a block is broken by a player
- **[BlockBurnEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockBurnEvent.html)**: Called when a block is destroyed as a result of being burnt by fire
- **[BlockCanBuildEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockCanBuildEvent.html)**: Called when we try to place a block, to see if we can build it here or not
- **[BlockDamageEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockDamageEvent.html)**: Called when a block is damaged by a player
- **[BlockDispenseEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockDispenseEvent.html)**: Called when an item is dispensed from a block
- **[BlockExpEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockExpEvent.html)**: An event that's called when a block yields experience
- **[BlockExplodeEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockExplodeEvent.html)**: Called when a block explodes
- **[BlockFadeEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockFadeEvent.html)**: Called when a block fades, melts or disappears based on world conditions
- **[BlockFormEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockFormEvent.html)**: Called when a block is formed or spreads based on world conditions
- **[BlockFromToEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockFromToEvent.html)**: Represents events with a source block and a destination block, currently only applies to liquid (lava and water) and teleporting dragon eggs
- **[BlockGrowEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockGrowEvent.html)**: Called when a block grows naturally in the world
- **[BlockIgniteEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockIgniteEvent.html)**: Called when a block is ignited
- **[BlockMultiPlaceEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockMultiPlaceEvent.html)**: Fired when a single block placement action of a player triggers the creation of multiple blocks
- **[BlockPhysicsEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockPhysicsEvent.html)**: Thrown when a block physics check is called
- **[BlockPistonEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockPistonEvent.html)**: Called when a piston block is triggered
- **[BlockPistonExtendEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockPistonExtendEvent.html)**: Called when a piston extends
- **[BlockPistonRetractEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockPistonRetractEvent.html)**: Called when a piston retracts
- **[BlockPlaceEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockPlaceEvent.html)**: Called when a block is placed by a player
- **[BlockRedstoneEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockRedstoneEvent.html)**: Called when a redstone current changes
- **[BlockSpreadEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/BlockSpreadEvent.html)**: Called when a block spreads based on world conditions
- **[EntityBlockFormEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/EntityBlockFormEvent.html)**: Called when a block is formed by entities
- **[LeavesDecayEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/LeavesDecayEvent.html)**: Called when leaves are decaying naturally
- **[NotePlayEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/NotePlayEvent.html)**: Called when a note block is being played through player interaction or a redstone current
- **[SignChangeEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/block/SignChangeEvent.html)**: Called when a sign is changed by a player

###Inventory Events
- **[BrewEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/inventory/BrewEvent.html)**: Called when the brewing of the contents inside the brewing stand is complete
- **[CraftItemEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/inventory/CraftItemEvent.html)**: Called when the recipe of an item is completed inside a crafting matrix
- **[FurnaceBurnEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/inventory/FurnaceBurnEvent.html)**: Called when an itemstack is successfully burned as fuel in a furnace
- **[FurnaceExtractEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/inventory/FurnaceExtractEvent.html)**: This event is called when a player takes items out of the furnace
- **[FurnaceSmeltEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/inventory/FurnaceSmeltEvent.html)**: Called when an itemstack is successfully smelted in a furnace
- **[InventoryClickEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/inventory/InventoryClickEvent.html)**: Called when a player clicks a slot in an inventory
- **[InventoryCloseEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/inventory/InventoryCloseEvent.html)**: Called when a player closes an inventory
- **[InventoryCreativeEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/inventory/InventoryCreativeEvent.html)**: Called when a player in creative mode puts down or picks up an item in their inventory / hotbar and when they drop items from their inventory while in creative mode
- **[InventoryDragEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/inventory/InventoryDragEvent.html)**: This event is called when the player drags an item in their cursor across the inventory
- **[InventoryMoveItemEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/inventory/InventoryMoveItemEvent.html)**: Called when some entity or block tries to move items directly from one inventory to another
- **[InventoryOpenEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/inventory/InventoryOpenEvent.html)**: Called when a player opens an inventory
- **[InventoryPickupItemEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/inventory/InventoryPickupItemEvent.html)**: Called when a hopper or hopper minecart picks up a dropped item
- **[PrepareItemCraftEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/inventory/PrepareItemCraftEvent.html)**: Called when a player prepares to craft an item

###World Events
- **[ChunkLoadEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/world/ChunkLoadEvent.html)**: Called when a chunk is loaded
- **[ChunkPopulateEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/world/ChunkPopulateEvent.html)**: Called when a new chunk has finished being populated
- **[ChunkUnloadEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/world/ChunkUnloadEvent.html)**: Called when a chunk is unloaded
- **[PortalCreateEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/world/PortalCreateEvent.html)**: Called when a portal is created
- **[SpawnChangeEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/world/SpawnChangeEvent.html)**: Called when a world's spawn changes
- **[StructureGrowEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/world/StructureGrowEvent.html)**: Called when an organic structure attempts to grow
- **[WorldInitEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/world/WorldInitEvent.html)**: Called when a world is initializing
- **[WorldLoadEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/world/WorldLoadEvent.html)**: Called when a world is loaded
- **[WorldSaveEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/world/WorldSaveEvent.html)**: Called when a world is saved
- **[WorldUnloadEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/world/WorldUnloadEvent.html)**: Called when a world is unloaded


###Vehicle Events
- **[VehicleBlockCollisionEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/vehicle/VehicleBlockCollisionEvent.html)**: Called when a vehicle collides with a block
- **[VehicleCollisionEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/vehicle/VehicleCollisionEvent.html)**: Called when a vehicle collides
- **[VehicleCreateEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/vehicle/VehicleCreateEvent.html)**: Called when a vehicle is created
- **[VehicleDamageEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/vehicle/VehicleDamageEvent.html)**: Called when a vehicle receives damage
- **[VehicleDestroyEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/vehicle/VehicleDestroyEvent.html)**: Called when a vehicle is destroyed
- **[VehicleEnterEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/vehicle/VehicleEnterEvent.html)**: Called when an entity enters a vehicle
- **[VehicleEntityCollisionEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/vehicle/VehicleEntityCollisionEvent.html)**: Called when a vehicle collides with an entity
- **[VehicleExitEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/vehicle/VehicleExitEvent.html)**: Called when a living entity exits a vehicle
- **[VehicleMoveEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/vehicle/VehicleMoveEvent.html)**: Called when a vehicle moves
- **[VehicleUpdateEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/vehicle/VehicleUpdateEvent.html)**: Called when a vehicle updates

###Server Events
- **[MapInitializeEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/server/MapInitializeEvent.html)**: Called when a map is initialized
- **[PluginDisableEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/server/PluginDisableEvent.html)**: Called when a plugin is disabled
- **[PluginEnableEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/server/PluginEnableEvent.html)**: Called when a plugin is enabled
- **[RemoteServerCommandEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/server/RemoteServerCommandEvent.html)**: Called when a command is recieved over RCON
- **[ServerCommandEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/server/ServerCommandEvent.html)**: Called when a command is run from the server console
- **[ServerListPingEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/server/ServerListPingEvent.html)**: Called when the server is pinged
- **[ServiceRegisterEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/server/ServiceRegisterEvent.html)**: Called when a service is registered
- **[ServiceUnregisterEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/server/ServiceUnregisterEvent.html)**: Called when a service is unregistered

###Weather Events
- **[LightningStrikeEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/weather/LightningStrikeEvent.html)**: Called when lightning strikes in a world
- **[ThunderChangeEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/weather/ThunderChangeEvent.html)**: Called when the thunder state in a world changes
- **[WeatherChangeEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/weather/WeatherChangeEvent.html)**: Called when the weather in a world changes

###Hanging Entity Events
- **[HangingBreakByEntityEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/hanging/HangingBreakByEntityEvent.html)**: Called when a hanging entity is removed by an entity
- **[HangingBreakEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/hanging/HangingBreakEvent.html)**: Called when a hanging entity is removed
- **[HangingPlaceEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/hanging/HangingPlaceEvent.html)**: Called when a hanging entity is created

###Painting Events
- **[PaintingBreakByEntityEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/painting/PaintingBreakByEntityEvent.html)**: Called when a painting is removed by an entity
- **[PaintingBreakEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/painting/PaintingBreakEvent.html)**: Called when a painting is removed
- **[PaintingPlaceEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/painting/PaintingPlaceEvent.html)**: Called when a painting is created


###Enchantment Events
- **[EnchantItemEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/enchantment/EnchantItemEvent.html)**: Called when an ItemStack is successfully enchanted
- **[PrepareItemEnchantEvent](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/event/enchantment/PrepareItemEnchantEvent.html)**: Called when an ItemStack is inserted in an enchantment table
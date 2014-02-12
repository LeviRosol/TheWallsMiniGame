TheWallsMiniGame
================
About The Walls Minigame
The walls was a map created by hypixel to work with redstone and to stand alone by itself. After is huge popularity, many people have been wanting server mods so that they can get the minigame working on the own server without having to reset the map by itself.


The Walls plugin is a plugin the fully automates the walls and also makes them fully customisable.


**Features**
* Fully Automated walls
* Chest restocking/Block Restoring
* Support any walls map
* Sorts players into teams
* Can only build in the correct areas
* Written Tutorial
* A written tutorial for the plugin can be found here.

**YouTube Tutorial**
Heres the link. The walls tutorial

In Portuguese: The walls tutorial in Portuguese (Thanks to AbsintoJ)

Tutorial 2: The walls tutorial (Thanks to yanniclord)

Tutorial 3: The walls tutorial (Thanks to VariationVault)

**Installation**
Put into the plugin folder like any other minecraft server mod. Needs TagAPI to work. Get it Here: TagAPI

**Source**
Source can be found here: https://github.com/LeviRosol/TheWallsMiniGame

**Commands and Permissions**
* `/Walls Help` permission for the commands they can use  Shows the commands that they can use
* `/Walls Join <ArenaName>` walls.join  Allows join to join a walls arena
* `/Walls Leave`  walls.join  Allows you to leave the walls
* `Select a region with a brick`  walls.create  Allows you to select a region with a brick
* `/Walls Create <ArenaName>` walls.create  Allows you to create arenas
* `/Walls Delete` walls.delete  Allows you to delete arenas
* `/Walls Tool` walls.create  Gives you the wand for creating the walls
* `/Walls Stop` walls.stop  Allows you to stop all arenas - Buggy till next update, use at risk
* `/Walls Stop <ArenaName>` walls.stop  Allows you to stop a specific walls arena - Buggy till next update, use at risk
* `/Walls Start`  walls.start Allows you to start the walls arena that you are in
* `/Walls Start <ArenaName>`  walls.start Allows you to start a specific walls arena
* `/Walls ListRegions <RegionType> <ArenaName>` walls.listregions Allows you to see the regions created
* `/Walls ShowRegion <RegionType> [Region-ID] <ArenaName>`  walls.showregions The sender get to see the arena regions highlighted in glowstone
* `/Walls DropLocation <ArenaName>` walls.create  Adds an area that will disappear went the walls need to drop
* `/Walls BuildRegion`  walls.create  Allows people to build between the two different points
* `/Walls SetWarp <WarpName> <ArenaName>` walls.create  Sets warps for the walls. Lobby, Lose, Win
* `/Walls AddSpawn <Colour> <ArenaName>`  walls.create  Adds a persons spawn point in the walls. Red, Blue, Green, Yellow
* `/Walls ArenaInfo <ArenaName>`  walls.info  Checks the infomation about the arenas
* `/Walls Time <Operator> <Time> <ArenaName>` walls.time  Set the time the arena will last in seconds
* `/Walls Broadcast <Operator> <Time> <ArenaName>`  walls.broadcast Will tell people in the arena how long it is till the walls drop
* `/Walls AC <Operator> [Command] <ArenaName>`  walls.commands  Edits the Allowed Commands that are allowed to be used while playing the walls
* `/Walls MinPlayers <integer> <ArenaName>` sets the minimum number of players needed to start a new game.
* `/Walls Save <Config/Arena> [ArenaName]`  walls.save, walls.save.config, walls.save.arenas  Allows people to save the config and arenas
* `/Walls Reload <Kits>`  walls.reload, walls.reload.kits Reloads the kits config
* `See if there is an update when they join`  walls.updates Checks if there is an update for the walls and then tells them if there is one when they join
* `Join using a sign` walls.signjoin  Click a sign and it will allow you to join the game

**Sign Walls**
How to create a join sign:

Line 1: `[walls]`

Line 2: `join`

Line 3: `<arenaname>`

How to create a kit sign:

Line 1: `[walls]`

Line 2: `kit`

Line 3: `<Kit name>`

Permission: walls.signwall

To break/remove the wall punch it with a brick

More coming soon...

**Permissions for kits:**

Walls.kit.* : Permission to use all the kits

Walls.kit.<kitname> : Permission to use a certain kit

**Future Updates**
* ~~Allow for a configurable minimum players setting~~
* Config setting for time to start game
* Team Chat
* Spectator mode
* Prize kits
* Right menu display for team list / counts
* Top menu for latest kill / announcements
* Don't get kicked from the game if you leave and join again (after 30 seconds or about)
* Timer signs - Reset count down (percent based) - Signs for within arenas showing play time left 

**Future Updates from original Author**
* More optimisation
* An api
* Can teleport to spawns just in case you lose them
* List the spawns and their locations
* More customisability
* Any bug fixes that need to be done
* Neaten the coding
* Update chat so it looks nicer
* Punch a block so that you are marked as ready
* Can edit an arena, Once doing this, you don't need to put the Arena Name at the end of every command
* Team selection

**Demonstration Servers**

play.stormcraft.net

**Read before posting about a bug**
Make sure that you have TagAPI installed or the plugin won't work.

The server may crash when creating an arena, because it has not been fully optimised yet, but that will be coming soon

If you are going to post a bug, make sure you try to include a link to an error log. Also tell me what you did, or when it happened that these errors started happening

![ValheimPlus Logo](https://raw.githubusercontent.com/nxPublic/ValheimPlus/master/logo.png)

# ValheimPlus
A HarmonyX Mod aimed at improving the gameplay quality of Valheim. The mod includes several different main features including modifiers to ingame stats of players, buildings and entities and a sophisticated system to build and place objects with high precision and a system to modify already placed objects with high precision. The general goal is to provide V+ as a base modification for your gameplay to increase quality of life, change difficulty or have a better experience in general. The mod also comes with a version and configuration control system for servers and users, allowing servers to make sure that only people with the same configuration are able to join their servers.

# ValheimPlus Server Hosting
Below you can find a list of hosting companies that are supporting ValehimPlus with good prices and easy installation.

[![GPortal](http://valheim.plus/gportal/banner.jpg)](https://www.g-portal.com/valheim)
[![ZapHosting](http://valheimplus.com/zap/692x127.jpg)](https://zap-hosting.com/valheimplus)
[![GFXHosting](https://www.gtxgaming.co.uk/wp-content/uploads/2021/02/valheim_plus_banner-3.png)](https://www.gtxgaming.co.uk/clientarea/aff.php?aff=2096)


# Features
All of these features can be adjusted by a configuration file. This also allows you to only enable very specific featues.


## Player

* Modification of stamina usage and regeneration
* Modification of stamina usage of all tools and weaponry
* Modification of carry weight
* Modification of food duration
* Modification of Unarmed Damage
* Modification of auto pickup range
* Option to force remove all screen shakes
* Modify the base amount of Unarmed damage multiplied by your unarmed skill level

## Fermenter, Beehive, Kiln and Furnace
* Modify Fermenter speed
* Modify Fermenter output amount
* Modify Beehive honey production speed
* Modify Beehive maximum honey
* Modify Furnace processing speed
* Modify Furnace maximum coal/ore
* Modify Kiln processing speed
* Modify Kiln maximum wood

## Workbench and Ward
* Modify Workbench radius
* Modify Ward radius

## Torches and Fireplaces
* Disable torches running out of fuel
* Disable fireplaces running out of fuel

## Time and Day Manipulation
* Modify total time of a day and night cycle
* Modify the speed of the time passing at night

## Structural Integrity
* Modify the structural integrity of the following materials by a modifier
  * Wood
  * Stone
  * Iron
  * Hardwood
* Disable structural integrity entirely, allowing you to place objects in free air.

## Player Hud
* Show the experience you gained for a skill in the top left corner
* Show the amount of items you have in your inventory when crafting or building a object. 

## Game Difficulty
* Modify the game difficulty multipliers applied to health and damage of enemies based on the amount of connected players.
* Change the range of where the game considers other players to be nearby.
* Add a additional amount of Players to the player count for the difficulty calculation.
* Set the difficulty calculation to a specific player count.

## Skill Experience
* Modify each skill's experience gain seperately by percent.

## Camera
* Change your FOV
* Change the maximum zoom out distance
* Change the maximum zoom out distance when in a boat

## Wagon
* Modify the physical weight of the Wagon received by items inside
* Modify the base physical weight

## Items
* Remove Item teleport prevention from all items
* Reduce Item weight of all items by %
* Modify maximum item stack size by %

## Server
* Remove Password requirement for server
* Modify maximum Players on a server
* Modify auto save interval
* Modify server data rate in kilobyte
* Automatic server configuration sync when a user joins the server to sync the configuration of V+

## Map
* Activate shared position on map automatically
* Setting to force other people to share their position with you
* Remove death marker on the map on collecting your tombstone

### Shared map system
Allows you to see the explored areas on the map of other players on the server if they have their position on the map shared ingame.
*You currently only receive exploration when you are online.*

### Player visibility
Allows you to be visible on the server map by default when joining.

### Prevent player from turning off visibility
Prevents players on the server from making themselves invisible on the map.

## Custom Keybinds
* Hotkey options for fowards and backwards roll.

# Building
* Remove Building "Invalid Placement" restriction
* Remove Building Object deterioration by weather.
* Advanced Building Mode
* Advanced Editing Mode
* Structural Integrity modification system

### Advanced Building Mode | Video : https://i.imgur.com/ddQCzPy.mp4
*How it works. All mentioned hotkeys can be modified.*
1. You freeze the item by pressing the configured key (F1 is default).
2. You can modify the item position and rotation with the following key combinations:
  * Arrow Up/Down/Left/Right = moves the building object in the respective direction.
  * Arrow Up/Down + Control = moves the building object up and down
  * ScrollWheel = rotates the building object on the Y axis.
  * ScrollWheel + Control = rotates the building object on the X axis.
  * ScrollWheel + left Alt = rotates the building object on the Z axis.
  * Numpad plus/minus to either increase or decrease the speeds, press SHIFT in addition to raise/lower by 10 instead of 1
  (Pressing Shift at any moment in time increases the distance/rotation angle by *3)
  3. Build the object with a mouse click.
  
**NOTES:**
* *Building objects build with this system are not excempt from the structure/support system!*
* *They are also not able to be build inside dungeons or placed in restricted areas!*

### Advanced Editing Mode | Video : https://imgur.com/DMb4ZUv.mp4
How it works.
*You cannot be in Build mode (hammer, hoe or terrain tool).*
1. You select the item with the configured key (Numpad0 is default).
2. You can modify the item position and rotation with the following key combinations:
* Arrow Up/Down/Left/Right = moves the building object in the respective direction.
* Arrow Up/Down + Control = moves the building object up and down
* ScrollWheel = rotates the building object on the Y axis.
* ScrollWheel + Control = rotates the building object on the X axis.
* ScrollWheel + left Alt = rotates the building object on the Z axis.
* resetAdvancedEditingMode HotKey = resets the position and rotation to the inital values.
* Numpad plus/minus to either increase or decrease the speeds, press SHIFT in addition to raise/lower by 10 instead of 1
(Pressing Shift at any moment in time increases the distance/rotation angle by *3)
3. Press the confirmPlacementOfAdvancedEditingMode Hotkey to confirm the changes.
3. *To Abort the editing mode and reset the object press abortAndExitAdvancedEditingMode HotKey)*

**NOTES:**
* *People in multiplayer will not be able to see the item being moved until you confirm the placement.* 
* *Building objects build with this system are not excempt from the structure/support system!




# Installation Instructions
We supply 4 different versions of V+ with every release since version 0.8. You can find detailed instructions on how to install these varients below.

**ATTENTION FOR MULTIPLAYER**: The game and the server both should have this mod installed to prevent all kinds of different issues. If you have the mod installed and then have friends join over steam they should have the mod as well.

## **[Game] Windows (Steam)**

1. Download the [latest package called WindowsClient.zip over this link](https://github.com/nxPublic/ValheimPlus/releases/latest/). *(Scroll down and click "assets")*
2. Locate your game folder, go into steam and :
   1. Right click the valheim game in your steam library
   2. "Go to Manage" -> "Browse local files"
   2. Steam should open your game folder for you when clicked
3. Unzip the contents of WindowsClient.zip into the Valheim root folder.
   
**Please read the section about Server Config & Version Control (About Version Enforcement) below.**


## **[Server] Windows**

[Easy to setup and ready to use ValheimPlus servers can be rented here at ZAP-Hosting.com !](https://zap-hosting.com/valheimplus)

We will not explain how you create a dedicated server. This will only explain how you install the mod.

1. Download the [latest package called WindowsServer.zip over this link](https://github.com/nxPublic/ValheimPlus/releases/latest/). *(Scroll down and click "assets")*
2. Unpack the downloaded zip file it into your root server folder.

**Please read the section about Server Config & Version Control (About Version Enforcement) below.**


## **[Server] Unix**

[Easy to setup and ready to use ValheimPlus servers can be rented here at ZAP-Hosting.com !](https://zap-hosting.com/valheimplus)

We will not explain how you create a dedicated server. This will only explain how you install the mod.
1. Download the [latest package called UnixServer.zip over this link](https://github.com/nxPublic/ValheimPlus/releases/latest/). *(Scroll down and click "assets")*
2. Locate your server folder
3. Unpack all the contents into your root server folder.

*Make sure to execute 'chmod u+x start_server_bepinex.sh'*

*Make sure to run start_server_bepinex.sh*

**Uses libc6-dev**

**Please read the section about Server Config & Version Control (About Version Enforcement) below.**

# What if the game updates?
Game updates are unlikely to do more than partially break ValheimPlus at worst. In case you encounter any issues, use Steam's verify integrity feature- wait for it to download/update all files.
Then simply unpack the *valheim_Data* folder from the downloaded last available v+ version package into your game folder again.
This should resolve any issues related. If you continue to have issues, contact the help channel in our discord server.

# Server Config & Version Control (About Version Enforcement)
* If you have enforceConfiguration and enforceMod enabled, only people with the same configuration and mod version can join your server and you can only join servers with the same mod and configuration.
* If you have enforceConfiguration and enforceMod disabled, you can join every server including vanilla ones as long as they allow you to. 
*(Meaning they have either no v+ mod installed or enforceMod disabled)*
* If you have enforceConfiguration disabled and enforceMod enabled, you will be able to join every server with v+ installed as long as its the same version.

**This system is working 100% reliable and is issue free.**

**If you encounter problems, you have not properly set up the configuration or your server/client is not running v+**

# Join the Discord
We have several different channel including a showcase channel and alpha testing system, allowing you to always get the newest versions available to test out.

![ValheimPlus Icon](https://raw.githubusercontent.com/nxPublic/ValheimPlus/master/ico.png)
https://discord.gg/AmH6Va97GT

# Twitter
Is used to post about releases of ValheimPlus and to potentially reply to issues.
https://twitter.com/ValheimPlus

# Support on Patreon
Supporting this Project on Patreon will allow me to dedicate more of my free time into this project. It will also pay for server costs of our new domains and our upcoming discord bot.

https://www.patreon.com/valheimPlus


# Configuration File

The Config files name is supposed to be "valheim_plus.cfg" it needs to be placed in "BepInEx\config"

You can turn off and on every feature of V+ via the config file, by default all settings are turned off.

When you are hosting a server, your server configuration file overwrites the clients configuration file on connect. 

You only need to setup your server configuration file (located in the server files) when hosting a server with V+.

If you are hosting for your friends over steam, your friends will need v+ and they will receive your local settings from your game folder.


# Valheim Plus Compiler Requirements

How to setup the development enviroment to compile ValheimPlus yourself.

1. Download this package:
https://mega.nz/file/0UAlxQwK#47InGOb8ViI6GyBDArpbhkbMTBklXdyRSmAc4-BZpJY

2. Unpack into your Valheim root folder and overwrite every file when asked.

3. Download this repository or the executable version of the Publicizer.
Repo: https://github.com/MrPurple6411/Bepinex-Tools/releases/tag/1.0.0-Publicizer
Exec: https://mega.nz/file/oQxEjCJI#_XPXEjwLfv9zpcF2HRakYzepMwaUXflA9txxhx4tACA

4. Drag and drop all assembly_.dll files onto "AssemblyPublicizer.exe"

5. Define Enviroment Variable `VALHEIM_INSTALL` with path to Valheim Install Directory  
example: `setx VALHEIM_INSTALL "C:\Program Files\Steam\steamapps\common\Valheim" /M`

# Credits

* Kevin 'nx#8830' J.- https://github.com/nxPublic
* Greg 'Zedle' G. - https://github.com/zedle
* Paige 'radmint' N. - https://github.com/radmint
* TheTerrasque - https://github.com/TheTerrasque
* Bruno Vasconcelos - https://github.com/Drakeny
* GaelicGamer - https://github.com/GaelicGamer
* Doudou 'xiaodoudou' - https://github.com/xiaodoudou
* MrPurple6411#0415 - BepInEx Valheim version, AssemblyPublicizer
* Mehdi 'AccretionCD' E. - https://github.com/AccretionCD

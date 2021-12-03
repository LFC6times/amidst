Amidst
======

[![Build Status](https://travis-ci.org/toolbox4minecraft/amidst.svg?branch=master)](https://travis-ci.org/toolbox4minecraft/amidst)

## Using to output all structures to a certain file:
Put the build of Amidst in its own folder. Then, open a command prompt, and run

"java -jar -Xmx[ram allocated] [insert file name] > output.txt" 
(no quotes, and it is recommended to use -Xmx to increase memory, like -Xmx8g gives 8gb ram. The "> output.txt" puts the console output into a file output.txt)

Then, when the "Profile Selector" window appears, choose a vanilla 1.16 installation (1.16 to 1.16.5). Once Amidst loads, go to File, choose "New From Seed", and enter a world seed.
Go into Settings, ensure "Default World Type" is set to "Default", disable the following: Smooth Scrolling, Fragment Fading, and Restrict Maximum Zoom.
Change the Number of Threads as you see fit. Under Layers, ensure that the corresponding boxes for your chosen structure are ticked. For Witch Huts, ensure Overworld and Temple/Witch Hut Icons are enabled. All other choices may be disabled.

## What is Amidst?

Amidst is a tool to display an overview of a Minecraft world, without actually creating it.

Amidst **can**:

* render an overview of a world from a given seed and Minecraft version
* save an image of the map
* use a save game
* display biome information
* display slime chunks
* display end islands
* display the following structures
  * world spawn
  * strongholds
  * villages
  * witch huts
  * pillager outposts
  * jungle temples
  * desert temples
  * igloos
  * abandoned mine shafts
  * ocean monuments
  * ocean ruins
  * shipwrecks
  * buried treasures
  * nether fortresses
  * end cities

Amidst **cannot**:

* display changes that were applied to a save game like
  * changes made by world editors like MCEdit
  * changes made while loading the world in Minecraft
* find individual blocks or mobs like
  * diamond ore
  * cows

## Amidst has found a new home

Amidst was moved to a new location, since Skidoodle aka skiphs is too busy to maintain it. It has also found some new developers. One of them is DrFrankenstone, a.k.a. Treer, who is the developer of AmidstExporter. Skidoodle is still an owner of Amidst and agreed to move the project.

### Links

* [Download](https://github.com/toolbox4minecraft/amidst/releases)
* [FAQ](https://github.com/toolbox4minecraft/amidst/wiki/FAQ)
* [Wiki](https://github.com/toolbox4minecraft/amidst/wiki)
* [Reporting a Bug](https://github.com/toolbox4minecraft/amidst/wiki/Supporting-the-Development#reporting-a-bug) - please report bugs, so we can fix them
* [Requesting a Feature](https://github.com/toolbox4minecraft/amidst/wiki/Supporting-the-Development#requesting-a-feature)
* [Thread in the minecraftforum](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-tools/2970854-amidst-map-explorer-for-minecraft-1-14)
* [Project Page](https://github.com/toolbox4minecraft/amidst)
* [Supporting the Development](https://github.com/toolbox4minecraft/amidst/wiki/Supporting-the-Development)
* [License Text](https://github.com/toolbox4minecraft/amidst/blob/master/LICENSE.txt)

## What is my internet connection used for?

* Amidst **will** use web services provided by Mojang, e.g. to
  * display information about Minecraft versions.
  * display information about players like the name or the skin.
* Amidst **will** check for updates on every start.
* Amidst **will not** track you with Google Analytics, which was the case in older versions.

## Legal Information

* Amidst is **not** owned by or related to Mojang in any way.
* Amidst comes with **absolutely no warranty**.
* Amidst is free and open source software, licensed under the GPLv3.

## Screenshots

These screenshots are created from the seed 24922 using Amidst v4.0 and Minecraft 1.9.

![default](https://raw.githubusercontent.com/wiki/toolbox4minecraft/amidst/screenshots/screenshot_default_24922_default.png)

### The End Dimension

![The End Dimension](https://raw.githubusercontent.com/wiki/toolbox4minecraft/amidst/screenshots/screenshot_default_24922_end.png)

### Biome Highlighter

![Biome Highlighter](https://raw.githubusercontent.com/wiki/toolbox4minecraft/amidst/screenshots/screenshot_default_24922_biome-highlighter.png)

### Grid

![Grid](https://raw.githubusercontent.com/wiki/toolbox4minecraft/amidst/screenshots/screenshot_default_24922_grid.png)

### Slime Chunks

![Slime Chunks](https://raw.githubusercontent.com/wiki/toolbox4minecraft/amidst/screenshots/screenshot_default_24922_slime.png)

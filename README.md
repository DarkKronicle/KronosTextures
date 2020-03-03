# KronosTextures

By DarkKronicle and Chronos22Gamer

- [Overview](#overview)
- [Installation](#installation)
  - [1st method](#1st-method)
  - [2nd method](#2nd-method)
- [Features](#features)
- [Optifine Use](#optifine-use)
  - [color.properties](#colorproperties)
- [Credits](#credits)
- [Contributing/Questions](#contributingquestions)

## Overview

Only a couple textures have been used from other texturepacks (you can see all at the end of the document), we strive to make this pack as original as possible. This pack's goal is to improve everyday Minecraft without drastically changing the feel and look. This pack only works on 1.15 and _requires_ Optifine for many of the features. This texturepack is meant to be an add on to be an add on, not a texturepack you use alone, so feel free to add on any other texturepacks to improve generic looks.

We have also added textures from a game called [BombBrigaders](https://github.com/DarkKronicle/BombBrigaders), including panoramas and different messages from there. As well as random other builds we've made.

In this file there will be documentation on how different aspects of this texturepack were achieved and how you can use do it too.

## Installation

There are 2 main ways to install this texturepack into Minecraft:

### 1st method

Download the zip.

1. Download the texturepack by going to the Github repo and select `clone or download`, select download.
2. Move the downloaded file to your Minecraft resourcepack folder.
3. Reload the resourcepack and it should be there
    - If this doesn't work you may need to uncompress the zip file.

### 2nd method

Use GitHub clone function.

1. Open up a terminal and navigate to your Minecraft resource folder.
    - `cd PATHTOFILE`
2. Inside of this folder go to the GitHub page and select _`lone or download`, if you do not have SSH click `Use HTTP`. Copy this link.
3. Back in terminal run this command:
   - `git clone LINKHERE`
4. Wait for it to finish and you should have the full resourcepack. Later if you want to update you can simply navigate back to it and do:
   - `git pull`

## Features

The texturepack includes the following additions:

- New splashes and panorama.
- New loading screen
- BombBrigader death messages
- BombBrigader style messages
- Lightmaps for end and nether _(subject to change)_
- HD Font ([Credits](#credits))
- Durability colors
- XP orb colors
- XP text color
- End sky color
- Slime colors
- Enchantment glint
- Sky textures ([Credits](#credits))

## Optifine Use

In this texturepack how optifine is used to provide more ways to customize minecraft. Mainly we use this to change hardcoded colors and provide randomness to different textures.

Go to the docs to learn more: [Optifine docs](https://github.com/sp614x/optifine/tree/master/OptiFineDoc/doc) 

In this section all files are from ~/optifine/

### color.properties

Inside of here there are multiple parameters we use:

- `text.xpbar=fffff` Sets xp text to white
- `screen.loading.progress=6628e2` Sets loading screen progress bar to purple.
- `screen.loading=000000` Sets loading screen background to black.
- `screen.loading.outline=9e9e9e` Sets loading screen progress bar outline to white.
- `xporb.time=50000` Sets how fast the xp bar flickers
- `sky.end=3b004d` Sets end sky color to a dark purple.

## Credits

[HD Font (64x64)](https://www.planetminecraft.com/texture_pack/hd-minecraft-font---64x---default-style) ~/textures/font/ascii.png  
[Real Nature](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/resource-packs/2416089-real-nature-resource-pack-photo-realistic-1-11-x-1) ~/optifine/sky/  
[Uncle Jam](https://www.youtube.com/channel/UCfg9squuCoQvPJt5tCWjTOg) Used his tutorials.

## Contributing/Questions

To contribute any textures or ideas go to the [BombBrigader Discord](https://discord.gg/NC6UBcy)

## Retro64 Mod
### This mod lets you play your favorite 1996 platformer game in a modern Minecraft world.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">I&#39;m working on a <a href="https://twitter.com/hashtag/Minecraft?src=hash&amp;ref_src=twsrc%5Etfw">#Minecraft</a> mod that runs the Super Mario 64 engine! It&#39;s very WIP right now but here&#39;s some highlights <a href="https://t.co/QCfzl10ip0">pic.twitter.com/QCfzl10ip0</a></p>&mdash; Dylan (@pdxdylan) <a href="https://twitter.com/pdxdylan/status/1437538144728064002?ref_src=twsrc%5Etfw">September 13, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

[Download Build Tool](https://github.com/Retro64Mod/retro64-GUI-build-utility/releases)

[Download Sound asset extractor (genfiles.exe)](https://github.com/Retro64Mod/sm64_asset_builder/releases)

[Download latest Mod file](https://github.com/Retro64Mod/Retro64Mod/releases)

Please keep in mind that the mod is in beta, you *will* encounter bugs

If you do encounter bugs, i'd appreciate them being reported [here](https://github.com/Retro64Mod/Retro64Mod.github.io/issues)

# Interested on how I did this?
Check out [this video](https://youtu.be/2yWKqc2rmHI) I made on the mod

# Making content on this mod?

Please credit me as @pdxdylan (Twitter handle), and make sure to say the mod is still a work in progress!

# Info
## Controls
- M key: Toggle between Minecraft mode and 'Retro64 mode'
- Z key: Open character selection menu
- Left Alt: Punch/Action

All of these bindings can be changed in settings

## HP
The health bars for each of the modes are separate. In Retro64 Mode, you have 4 hearts, or 8 hit points, corresponding to the SM64 health. You can heal by collecting XP orbs.

# FAQ

**Why do I need to compile the files myself?**

Due to DMCA reasons, unfortunately. While libsm64 gets *most* data from a ROM file, other data isn't able to be extracted (yet). If you're interested in helping with that and know C programming, feel free to submit a PR to [the original libsm64 repo](https://github.com/libsm64/libsm64)

**Does this mod work with shaders \(optifine\)?**

No, shaders are currently not supported.

**Is this mod compatible with this \[other mod\]?**

I doubt it, but i'll try to add compatibility with other mods in the future, although it's not a priority at the moment.

**Is there Multiplayer support?**

Yes, but it's very work in progress. If you want the best experience, I suggest playing in singleplayer for now!

**Why do I need `sm64.dll`?**

This file contains all the main code to run the mod. It's based on the SM64 Decomp and libsm64 projects. My fork is open source and available [here](https://github.com/Retro64Mod/libsm64-retro64)

**Why do I need `genfiles.exe`?**

This tool extracts sound assets from the ROM. It is not required if you don't want sound.

This mod requires [Minecraft Forge](https://files.minecraftforge.net/net/minecraftforge/forge/)

## Installation Instructions (Windows)
1. Install [MSYS2](https://www.msys2.org/) If you already have it installed, you may need to fully un-install it and install the latest version. **Old versions sometimes do not work properly**. So if you are encountering issues, be sure to re-install MSYS2
2. Download the Build tool linked above
3. Launch the Build tool and press "Get Versions". If it's your first time running this, it might take a while.
4. Select the version of the DLL to compile. You should select the same version as the mod (i.e if the mod is 1.18.2-1.0.0, select that in the version list)
5. Make sure MSYS2 points towards the folder where you installed MSYS2
6. Press "Compile" and wait.
7. Once it is finished, a folder will open. Take `sm64.dll` and put it in your Minecraft's mods folder.
8. Take the mod file (.jar) and also put it in your Minecraft's mods folder.
9. If you want audio support, also take the genfiles.exe linked above and put it in your Minecraft's mods folder.
10. Place your US ROM called (in .z64 format) in your Minecraft's mods folder. This mod only accepts the US .z64 version (`sha1: 9bef1128717f958171a4afac3ed78ee2bb4e86ce`)
11. You should end up with **4 files total** for this mod in your mods folder
12. Launch the game. 

## Installation Instructions (Linux)
For Linux, you'll have to compile the mod manually. This guide is for Debian based distros, but should work with the equivilant commands in other distros.
1. Install Dependencies by running the following commands
```sh
sudo apt-get update
sudo apt-get install build-essential git python3 libsdl2-dev
```
2. Clone the libsm64-retro64 repository, and enter it. This command will grab the latest version
```sh
git clone https://github.com/Retro64Mod/libsm64-retro64
cd libsm64-retro64
```
3. Build the repository by running the following command
```sh
make
```
4. Copy the `libsm64.so` file in the `dist` directory into your Minecraft mods folder.
5. Take the mod file (.jar) and also put it in your Minecraft's mods folder.
6. **Audio is currently not supported, but is coming in a future version!**
7. Place your US ROM called (in .z64 format) in your Minecraft's mods folder. This mod only accepts the US .z64 version (`sha1: 9bef1128717f958171a4afac3ed78ee2bb4e86ce`)
8. Launch the game. 

Note: Updates might require performing the compilation process again

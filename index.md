## Retro64 Mod
### This mod lets you play your favorite 1996 platformer game in a modern Minecraft world.

![Demo Video](https://i.imgur.com/8ZrVVpv.gifv)

[Download Build Tool](https://github.com/Retro64Mod/retro64-GUI-build-utility/releases)

[Download Sound asset extractor (genfiles.exe)](https://github.com/Retro64Mod/sm64_asset_builder/releases)

[Download latest Mod file](https://github.com/Retro64Mod/Retro64Mod/releases)


# Interested on how I did this?
Check out [this video](https://youtu.be/2yWKqc2rmHI) I made on the mod

# FAQ

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


## Installation Instructions
This mod requires [Minecraft Forge](https://files.minecraftforge.net/net/minecraftforge/forge/)
1. Install [MSYS2](https://www.msys2.org/) If you already have it installed, you may need to fully un-install it and install the latest version. **Old versions sometimes do not work properly**
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

Note: Updates might require performing the compilation process again

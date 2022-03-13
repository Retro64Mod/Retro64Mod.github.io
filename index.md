## Retro64 Mod
### This mod lets you play your favorite 1996 platformer game in a modern Minecraft world.

[Download Build Tool](https://github.com/Retro64Mod/retro64-GUI-build-utility/releases)

[Download Sound asset extractor (genfiles.exe)](https://github.com/Retro64Mod/sm64_asset_builder/releases)

[Download latest Mod file](https://github.com/Retro64Mod/Retro64Mod.github.io/releases)

## Installation Instructions
This mod requires [Minecraft Forge](https://files.minecraftforge.net/net/minecraftforge/forge/)
1. Install [MSYS2](https://www.msys2.org/)
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

Note: Every version update might require performing the compilation process again

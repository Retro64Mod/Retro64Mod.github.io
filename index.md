## Retro64 Mod
### This mod lets you play your favorite 1996 platformer game in a modern Minecraft world.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">I&#39;m working on a <a href="https://twitter.com/hashtag/Minecraft?src=hash&amp;ref_src=twsrc%5Etfw">#Minecraft</a> mod that runs the Super Mario 64 engine! It&#39;s very WIP right now but here&#39;s some highlights <a href="https://t.co/QCfzl10ip0">pic.twitter.com/QCfzl10ip0</a></p>&mdash; Dylan (@pdxdylan) <a href="https://twitter.com/pdxdylan/status/1437538144728064002?ref_src=twsrc%5Etfw">September 13, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

[Download latest Mod file](https://github.com/Retro64Mod/Retro64Mod/releases/download/1.18.2-1.0.13/retro64-1.18.2-1.0.13.jar)

Please keep in mind that the mod is in beta, you *will* encounter bugs

If you do encounter bugs, i'd appreciate them being reported [here](https://github.com/Retro64Mod/Retro64Mod.github.io/issues)

Download the latest release of the mod [here](https://github.com/Retro64Mod/Retro64Mod/releases/tag/1.18.2-1.0.13). Currently compatible with Minecraft 1.18.2

If you want to access beta versions of the mod before they're released, check [this link](https://github.com/Retro64Mod/Retro64Mod/actions) for the most recent build of the mod. Note that these may not be stable and it's still suggested to go with the [official release](https://github.com/Retro64Mod/Retro64Mod/releases/tag/1.18.2-1.0.13). You also need to be logged into GitHub to be able to download beta versions.

# Interested on how I did this?
Check out [this video](https://youtu.be/2yWKqc2rmHI) I made on the mod

# Making content on this mod?

Please credit me as @pdxdylan (Twitter handle), and make sure to say the mod is still a work in progress!

# Info
## Controls
- M key: Toggle between Minecraft mode and 'Retro64 mode'
- Z key: Open character selection menu
- Left Alt: Punch/Action
- Sneak key (usually Shift): Crouch

All of these bindings can be changed in settings

## HP
The health bars for each of the modes are separate. In Retro64 Mode, you have 4 hearts, or 8 hit points, corresponding to the SM64 health. You can heal by collecting XP orbs.

# FAQ

**Does this mod work with shaders \(optifine\)?**

No, shaders are currently not supported.

**Is this mod compatible with this \[other mod\]?**

I doubt it, but i'll try to add compatibility with other mods in the future, although it's not a priority at the moment.

**Is there Multiplayer support?**

Yes, but it's very work in progress. If you want the best experience, I suggest playing in singleplayer for now!

This mod requires [Minecraft Forge](https://files.minecraftforge.net/net/minecraftforge/forge/)

\* Note: For Windows, **Micosoft's antivirus (Windows Defender) might cause issues with running the mod**. This is due to the audio extraction currently requiring an exe file to work. If you know your way around the SM64 audio engine format and want to help fix this, check out the audio branch in the libsm64-retro64 repo (specifically, [this file](https://github.com/Retro64Mod/libsm64-retro64/blob/audio/src/decomp/tools/convUtils.c#L11-L18) as it's what i've been working on to properly do audio asset conversion.

## Installation Instructions (Windows, Linux, and Mac)
1. Download the latest mod version and un-zip it.
2. Take the mod file (.jar) and put it in your Minecraft's mods folder.
3. Place your US ROM (in .z64 format) in your Minecraft's mods folder. This mod only accepts the US .z64 version (`sha1: 9bef1128717f958171a4afac3ed78ee2bb4e86ce`)
4. Launch the game. 

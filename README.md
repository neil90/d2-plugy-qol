# Diablo II QOL Mod Pack

This is a mod pack for Diablo II v1.13d that brings together the best quality-of-life features I have found to maximize the singleplayer experience.

![D2LOD PlugY QOL Mod Pack](https://i.imgur.com/F2wfSek.jpg)

## What's Included

- [PlugY](http://plugy.free.fr/en/index.html) - adds unlimited stash, shared stash, infinite respec, all runewords.
- [BaseMod](https://d2mods.info/forum/viewtopic.php?t=65492) - removes singleplayer FPS cap, adds auto gold pickup.
- [FontFix](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#fixedfont) - makes 5s look like 5s instead of 6s.
- [NoIntro](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#nointro) - skip the intro videos when you boot the game.
- [DropMod](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#betterdrops) - 2X as likely to find uniques, 1.5X to find sets, no change to runes.
- [KeepEquip](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#equipmentdeath) - keep your equipment when you die (I play HC so I don't care about this).
- [PODQOL](https://github.com/Synial/SynFilter/tree/cd4ab9d8b51320973c7b3df9c90b74b3d1ea8f91/xfiles) - adds the loot filter from [Path of Diablo](https://pathofdiablo.com/).
- [D2HD](https://drive.google.com/drive/folders/1hLbrYs_U7eVcK-bWOom_Lr2_Y839AVba) - adds additional widescreen resolutions.

### My Custom Changes

**Sorceress**
- Spell cooldowns removed.

**Amazon**
- Arrows stack to 500.
- Strafe no longer makes grunting sound.

**Druid**
- Lycanthropy duration increased 50%.
- Can summon all beasts at same time.

## How To Install

- Purchase [registration keys](https://us.shop.battle.net/en-us/family/diablo-ii) from Blizzard.
- Install [D2 + LOD v1.12](https://mega.nz/#!e9thyD6A!ExGJuZUtvRJ2c8DrxSL0ihCouh-ARbdVxODXIqVt3dc).
- Install [Patch v1.13c](http://ftp.blizzard.com/pub/diablo2exp/patches/PC/LODPatch_113c.exe).
- Install [Patch v1.13d](http://ftp.blizzard.com/pub/diablo2exp/patches/PC/LODPatch_113d.exe).
- Install [Glide](http://www.svenswrapper.de/english/files.html).
- Install [PlugY](http://plugy.free.fr/en/index.html).
- Modify the properties of ``Diablo II.exe``, ``Game.exe``, and ``PlugY.exe`` to run as administrator and as Windows XP (SP 3).
- Modify the PlugY shortcut to have ``"C:\your\path\to\Diablo II\Mod PlugY\PlugY.exe" -3dfx -direct -txt`` as the target.
- Download this [zipfile](https://github.com/whipowill/d2-plugy-qol/archive/master.zip) and merge the files into your D2 folder.

### Optional AutoHotKey Script

Install [AutoHotKey](https://autohotkey.com/) and run this [script](https://raw.githubusercontent.com/whipowill/d2-plugy-qol/master/Diablo%20II/_autohotkey/AutoAttack.ahk) as administrator, which allows you to hold down spacebar to simulate repeated mouse clicks.  Makes melee characters a lot easier to play, but you can't type spaces while it's running (``/players8`` works w/ no space).

### How To Install w/ No Gameplay Changes

If you want to install these QOL mods but don't want any changes to the actual gameplay (no changes to drops or skills), then delete the ``Mod PlugY/data/global/`` folder from your install.

### Notes For Mac Users

You can install this the same way on Mac, only you will have to do it all through the [PortingKit](http://portingkit.com/en/) application.  It's a little trickier but it can be done.

### How To Uninstall

- Delete all the files you merged through this install process.
- Copy the files from ``_backups`` and paste them into your ``C:\your\path\to\Diablo II\`` folder.

## Notes

- Make sure you don't have the [CPU fix](http://europebattle.net/d2/tools) installed, as BaseMod already has it.
- When you first select a widescreen resolution the game will crash, but only the first time.
- The loot filter sometimes throws "invalid stat" errors in chat, but I don't think it breaks anything.

### Things I Want

- I wish I had the loot filter errors go away, they annoy me.
- I wish I had could shift-click between inventory and stash.

## Credits

- [PlugY](http://plugy.free.fr/en/index.html) provided by [Yohann Nicolas](http://plugy.free.fr/en/index.html) (v11.02).
- [BaseMod](https://www.dropbox.com/s/fj3f5smvxdld3kx/BaseMod106.zip) provided by [devurandom](https://d2mods.info/forum/viewtopic.php?t=65492) (v1.06).
- [FontFix](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#fixedfont) provided by [SnakeByteStudios](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/).
- [NoIntro](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#nointro) provided by [SnakeByteStudios](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/).
- [DropMod](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#betterdrops) provided by [SnakeByteStudios](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/).
- [KeepEquip](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#equipmentdeath) provided by [SnakeByteStudios](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/).
- [PODQOL](https://github.com/Synial/SynFilter/tree/cd4ab9d8b51320973c7b3df9c90b74b3d1ea8f91/xfiles) provided by [Path of Diablo](https://pathofdiablo.com/).
- [D2HD](https://drive.google.com/drive/folders/1hLbrYs_U7eVcK-bWOom_Lr2_Y839AVba) provided by [SlashDiablo](https://www.reddit.com/r/slashdiablo/comments/7z5uy1/hd_mod_and_maphack_new_release/).
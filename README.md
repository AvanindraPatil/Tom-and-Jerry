  
# Hello Tom & Jerry

**A mod for Hello Neighbor. Tom moved in next door, and you are Jerry.** Tom replaces the Neighbor with his own cartoon animations, and you sneak through the house as a tiny mouse, with mousetraps, slapstick catches and Spike the bulldog on your side.

<img width="2560" height="1440" alt="Screenshot (3440)" src="https://github.com/user-attachments/assets/a6bbbc8a-5e2e-43e1-afe9-f6bd7eaaad0e" />

> Unofficial fan project, free of charge, not affiliated with or endorsed by Warner Bros., tinyBuild, Dynamic Pixels or NetEase.

## Features

- **Tom as the Neighbor**, in every act, in the cutscenes and in the finale, with the Neighbor's AI hunting you as before.
- **Play as a tiny Jerry**: 42 cm against Tom's 190, in third person, with a free orbit camera. F8 switches to the game's kid and back.
- **40 mousetraps** around the house. They hold you, and they snap Tom too. Throw things at him and he sees stars.
- **Spike the bulldog**: press Q and he comes running to bite Tom.
- **Four ways to get caught**, in a shuffled round: by the tail, the chomp, the pot and the frying pan.

## Two downloads

| | Download | What you get |
|---|---|---|
| **Base mod** (start here) | `HelloTomJerry-1.0.0.zip` | Everything above. Tom and Jerry stay silent, and you hear the game's own music and footsteps with a few of its own effects. |
| **Audio add-on** (optional) | `HelloTomJerry-ChaseAudio-1.0.0.zip` | Tom's yowls and laughs, Jerry's taunts, Spike's barks, the traps, the pan and the chase music. |

The add-on contains no sounds. It makes them on your PC from your own copy of **Tom and Jerry Chase**, a free Android game, so it needs an emulator. It sends nothing anywhere.

## Requirements

- **Hello Neighbor** (the full game) on Steam, on Windows.
- For the add-on only: **[MuMu Player](https://www.mumuplayer.com/)** with **Tom and Jerry: Chase** installed in it, and about 3 GB of free disk space while it runs.

## Install the base mod

1. Download `HelloTomJerry-1.0.0.zip` from [Releases](../../releases) and unzip it anywhere.
2. Close Hello Neighbor and double-click **`Install.bat`**. It finds the game through Steam and installs the mod with [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS).
   Windows may warn about running a script from the internet: choose "More info", then "Run anyway".
3. Start Hello Neighbor from Steam as usual.

## Add the sounds (optional)

1. Install the base mod first, from the same release.
2. Install MuMu Player and start it.
3. In MuMu, open its app store (or the Play Store), find **Tom and Jerry: Chase** (NetEase, package `com.netease.tjglobal`) and install it. Wait for the download to finish. You do not have to play it.
4. Download `HelloTomJerry-ChaseAudio-1.0.0.zip`, unzip it anywhere, close Hello Neighbor and double-click **`Install-Audio.bat`**.
   It starts MuMu if needed, copies the game's data file out of it, makes the sounds and deletes the copy, in about a minute.

Afterwards the mod no longer needs MuMu or Tom and Jerry Chase, so you can uninstall both. Reinstalling or updating the base mod removes the sounds: run `Install-Audio.bat` again.

If the game is not listed in your region, the add-on cannot help: stay with the base mod.

## Controls

| Key | Action |
|---|---|
| Q | Jerry shouts for Spike |
| T | Jerry's taunt |
| F8 | Switch between Jerry and the game's kid; Tom stays |
| F9 | Tom on / off |

The rest are the game's own keys.

## Uninstall

- `Uninstall-Audio.bat` removes only the sounds.
- `Uninstall.bat` removes the mod and the sounds, and UE4SS too if this mod installed it.

## Troubleshooting

- **Another mod changes the Neighbor** (Hello Playtime, for example): the two fight over him, so use one at a time.
- **`Install-Audio.bat` says it could not connect**: in MuMu's settings, turn ADB debugging on (under Other) and run it again.
- **Logs**: `<Hello Neighbor>\HelloNeighbor\Binaries\Win64\tomjerry_lua.log`, and `ue4ss\UE4SS.log` in the same folder.

## Credits

- 3D models by [Guilherme Navarro](https://sketchfab.com/guinavarro.al), CC BY 4.0, changed for this mod (normals, bone names, Spike rigged, eyes opened, new animations): [Tom](https://sketchfab.com/3d-models/tom-rig-v2-multiversus-tom-and-jerry-dc60af62b20c49228584fd91451008a9), [Jerry](https://sketchfab.com/3d-models/jerry-rig-v2-multiversus-tom-and-jerry-a902931f1ff44002a8a900839c905233), [Spike](https://sketchfab.com/3d-models/spike-tom-and-jerry-80933ff944c5434996029ec3e2c70209).
- [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS) (MIT). The add-on's open-source parts are listed in its `THIRD-PARTY-NOTICES.txt`.
- Built with the help of an AI coding agent (Claude Code, Anthropic).

Tom, Jerry and Spike are characters of Warner Bros. Entertainment. Hello Neighbor is by tinyBuild / Dynamic Pixels. Tom and Jerry Chase is by NetEase. Use the add-on only with your own copy, for your own play, and do not share what it makes.

The MIT licence covers the mod's own code only. The models keep their CC BY 4.0 licence, and neither grants any right to the characters or the games.

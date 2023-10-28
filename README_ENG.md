# Attention! Ultra moved to the new [repository](https://github.com/redraz/Ultra-4ifir) 


# Ultra 4IFIR

[4IFIR Group on Telegram](https://t.me/UltraNX)

**ATTENTION! The author is not responsible for the consequences of installing Ultra 4IFIR; you proceed at your own risk.**
**However, based on my experience, console overclocking is completely safe for the console hardware, but it can pose risks to your data, game files, saves, or even damage system files. Therefore, it is highly recommended to use overclocking only on EmuNAND and always make timely save backups.**

## Project Description
The ultimate solution for maximum overclocking and configuration for your console!
Based on [4IFIR](https://github.com/rashevskyv/4IFIR), all licenses from the original project.

The basis of the pack is the Ultra Tuner, which was made due to [Ultrahand](https://github.com/ppkantorski/Ultrahand-Overlay).
- Allows you to configure GPU undervolting either in packages by switching the `GPU` from Base to Stage or vice versa, or precisely select the voltage for any of the frequencies.
- Ability to change the `CPU` voltage limit for Erista and Mariko, which will increase the CPU overclocking (or, when lowered, can fix game crashes). It also allows you to adjust the CPU undervolt.
- Select frequencies, timings and change `RAM` voltages.

## Installation

1. Unpack the [AIO](https://github.com/redraz/Ultra-4ifir/raw/main/AIO/AIO.zip) archive to the root of the SD card, replacing/merging files.
2. Open the `hb menu` (by launching a game with R held down), run `All-in-One Switch Updater`, and scroll down to `Custom downloads`.
3. First, just in case, select `Refresh AIO`, answer `yes` to the prompt; this will update the links in AIO.
4. Go back to `Custom downloads`, choose `[PACK] Ultra 4IFIR`, answer `yes` to the question.

### Clean Installation
If you encounter problems with the installation through `AIO`, you can perform a clean installation:
- Delete everything from the memory card except for the `Nintendo` and `emuMMC` folders, then unpack the [Ultra 4IFIR](https://github.com/redraz/Ultra-4ifir/raw/main/Ultra%204IFIR/Ultra%204IFIR.zip) archive onto the card.
- This will remove all mods for games and homebrew programs but will not affect your games and saves.

## Usage
**To change stages/settings:**
1. Open the Tesla menu (L+R+Up) - now replaced with `4esla`, press Right to access plugins.
2. Enter `Ultra`, and make a backup just in case - `Backup - Create`.
3. Now you are free to customize the system as you wish, or choose from the list of presets offered.
4. After completing the configuration, go to `Ultra` - `Tuner` - `Complete`, this will restart the console.
5. If you went too far with overclocking/stages, and your console fails to boot - simply enter `Hekate` and select booting in `Safe Mode`; unlike `Semi Stock`, the "safe mode" doesn't load the overclocking loader.kip, so you can boot into it without any issues and restore a backup/set the base stage.

### Standalone
 Standalone Tuner for OS Suite can be downloaded through a special [Updater](https://github.com/redraz/Ultra-4ifir/raw/main/Packages/Standalone%20Pack.zip). To install - unpack the archive to the console and restart for the plugin work.


### Addition
The `Ultra` `Updater` offers many additional features.
What there is in updater:
1. Installing different Hombrew apps, all from the original 4ifir as well as everything that Cooler posted. There’s also a useful hombrew.
2. Able to download any mod from 4MODS from Cooler, plus a couple of bonus mods.
3. Enable/Disable Background Online Services. By default, they are disabled, which reduces the console’s sleep consumption. But if you play the license often, it makes sense to enable them.
4. Adjust the frequency of background video recording, and its bitrate. It is required to apply after each switch on/off of background services due to the feature of work.
5. Change the combination of opening 4esla, which affects overlays and status monitor.
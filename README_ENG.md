# Ultra 4IFIR

[4IFIR Group on Telegram](https://t.me/For4ifir)

**ATTENTION! The author is not responsible for the consequences of installing Ultra 4IFIR; you proceed at your own risk.**
**However, based on my experience, console overclocking is completely safe for the console hardware, but it can pose risks to your data, game files, saves, or even damage system files. Therefore, it is highly recommended to use overclocking only on EmuNAND and always make timely save backups.**

## Project Description
The ultimate solution for maximum overclocking and configuration for your console!
Based on [4IFIR](https://github.com/rashevskyv/4IFIR), all licenses from the original project.

Includes Ultra Tuner based on [Ultrahand](https://github.com/ppkantorski/Ultrahand-Overlay)
- Allows you to configure GPU undervolting either in packages by switching the `GPU` from Base to ST or vice versa, or precisely select the voltage for any of the frequencies.
- Ability to change the `CPU` voltage limit for Erista and Mariko, which will increase the CPU overclocking ceiling (or, when lowered, can fix game crashes).
- Select frequencies and change `RAM` voltages.

## Installation

1. Unpack the [AIO](https://github.com/redraz/Ultra-4ifir/raw/main/AIO/AIO.zip) archive to the root of the SD card, replacing/merging files.
2. Open the `hb menu` (by launching a game with R held down), run `All-in-One Switch Updater`, and scroll down to `Custom downloads`.
3. First, just in case, select `Refresh AIO`, answer `yes` to the prompt; this will update the links in AIO.
4. Go back to `Custom downloads`, choose `Ultra 4IFIR`, answer `yes` to the question.

### Clean Installation
If you encounter problems with the installation through `AIO`, you can perform a clean installation:
- Delete everything from the memory card except for the `Nintendo` and `emuMMC` folders, then unpack the [Ultra 4IFIR](https://github.com/redraz/Ultra-4ifir/releases/latest/download/Ultra.4IFIR.zip) archive onto the card.
- This will remove all mods for games and homebrew programs but will not affect your games and saves.

## Usage
To change stages/settings:
1. Open the Tesla menu (L+R+Up) - now replaced with `Ultrahand`, press Right to access plugins. Enter `Ultra Tuner`, choose your console, `Mariko` or `Erista`, and press B.
2. All further configurations will happen this way: enter the desired menu, select the necessary setting, and press B to go back. The menu items will update, and new menus will appear on the main page.
3. Enter `Ultra Tuner` again; it has updated, and we have access to new items. Choose `Create Backup`, then select `Initialization Ultra`, and go back a couple of times by pressing B.
4. Now you are free to customize the system as you wish, or choose from the list of presets offered, whether from Cooler presets or from me.
5. Presets:
- Base - Real `RAM` frequency 2300MHz, GPU Base, timings 135650, voltage: cpu-1180mV, vddq-640mV, vdd2-1300mV
- ST9 - Real `RAM` frequency 2400MHz, GPU Stage, timings 455663, voltage: cpu-1180mV, vddq-630mV, vdd2-1250mV
- ST9+ - Real `RAM` frequency 2500MHz, GPU Stage, timings 555663, voltage: cpu-1235mV, vddq-630mV, vdd2-1250mV
- Ultra - Real `RAM` frequency 2476MHz, GPU Stage, timings 455663, voltage: cpu-1220mV, vddq-650mV, vdd2-1300mV
- Redraz - Real `RAM` frequency 2476MHz, GPU Stage, timings 555663, voltage: cpu-1220mV, vddq-630mV, vdd2-1225mV
- Test timings - Real `RAM` frequency 2265MHz, GPU Overvolt, timings 555663, voltage: cpu-1160mV, vddq-700mV, vdd2-1350mV
- Test MHz Ram - Real `RAM` frequency 2500MHz, GPU Overvolt, timings 111110, voltage: cpu-1160mV, vddq-700mV, vdd2-1350mV
6. After completing the configuration, go back to `Ultra Tuner` and choose `Complete Tuning`; this will clear unnecessary menu items and restart the console.
7. If you went too far with overclocking/stages, and your console fails to boot - simply enter `Hekate` and select booting in `Safe Mode`; unlike `Semi Stock`, the "safe mode" doesn't load the overclocking loader.kip, so you can boot into it without any issues and restore a backup/set the base stage.

### Addition

Now `4ifir Micro` is integrated into `Ultra Tuner` itself - just place Ultrahand on Kefir/OS Suite, put the Tuner in `/switch/.packages/` path, and initialize the stage. After that, Chifir's overclocking will work on Kefir/OS Suite.

In `Ultra Updater`, you can also install various homebrew applications, both from the original 4ifir composition and others, as well as access mods created by Cooler himself.
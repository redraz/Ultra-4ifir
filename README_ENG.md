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
4. Go back to `Custom downloads`, choose `[PACK] Ultra 4IFIR`, answer `yes` to the question.

### Clean Installation
If you encounter problems with the installation through `AIO`, you can perform a clean installation:
- Delete everything from the memory card except for the `Nintendo` and `emuMMC` folders, then unpack the [Ultra 4IFIR](https://github.com/redraz/Ultra-4ifir/raw/main/Ultra%204IFIR/Ultra%204IFIR.zip) archive onto the card.
- This will remove all mods for games and homebrew programs but will not affect your games and saves.

## Usage
**To change stages/settings:**
1. Open the Tesla menu (L+R+Up) - now replaced with `Uberhand`, press Right to access plugins. Enter `Ultra`, choose your console, `Mariko` or `Erista`, and press B.
2. Enter `Ultra` again; it has updated, and we have access to new items.
3. Now you are free to customize the system as you wish, or choose from the list of presets offered, whether from Cooler presets or from me.
4. After completing the configuration, go to `Ultra` - `Tuner` - `Complete`, this will restart the console.
5. If you went too far with overclocking/stages, and your console fails to boot - simply enter `Hekate` and select booting in `Safe Mode`; unlike `Semi Stock`, the "safe mode" doesn't load the overclocking loader.kip, so you can boot into it without any issues and restore a backup/set the base stage.

### Preset description
In brackets, values for Erista
Indicated real RAM frequency, in the 4ifir will be displayed higher by 200MHz

***Presets from Me - Core<Mega<Ultra<Red***
- Core - `RAM` 2300MHz (1996), GPU Base,
timings 225652, DVB 01
   - voltages: cpu-1160mV (1235), vddq-650mV, vdd2-1300mV
- Mega - `RAM` 2400MHz (2131), GPU Stage,
timings 425653, DVB 01
   - voltages: cpu-1200mV (1270), vddq-650mV, vdd2-1300mV
- Ultra - `RAM` 2500MHz (2188), GPU Stage,
timings 525653, DVB 01
   - voltages: cpu-1220mV (1320), vddq-650mV, vdd2-1300mV
- Red - `RAM` 2515MHz (2286), GPU Stage,
timings 555653 (626663), DVB 00
   - voltages: cpu-1220mV (1270), vddq-630mV, vdd2-1225mV (1300)

***Presets from Cooler - Base<ST9<ST9+***
- Base - `RAM` 2300MHz (1996), GPU Base,
timings 135652, DVB 02
   - voltages: cpu-1180mV (1270), vddq-640mV, vdd2-1300mV
- ST9 - `RAM` 2400MHz (1996), GPU Stage,
timings 345653, DVB 00
   - voltages: cpu-1180mV (1270), vddq-600mV, vdd2-1275mV
- ST9+ - `RAM` 2500MHz (1996), GPU Stage,
timings 555653, DVB 02
   - voltages: cpu-1235mV (1300), vddq-640mV, vdd2-1275mV

***Test - for ram test***
- Test timings - `RAM` 2131мгц (1862), GPU Overvolt,
timings 555653 (626663), DVB 02
   - voltages: cpu-1160mV (1235), vddq-700mV, vdd2-1350mV
- Test MHz Ram - `RAM` 2500мгц (2188), GPU Overvolt,
timings 111110, DVB 02
   - voltages: cpu-1160mV (1235), vddq-700mV, vdd2-1350mV

### Addition


In `Ultra` - `Updater`, you can also install various homebrew applications, both from the original 4ifir composition and others, as well as access mods created by Cooler himself.
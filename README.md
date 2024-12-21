# SkyTools

> [!TIP]
> To run any of the scripts, place them inside your main Skylanders dump directory and simply double-click.
> 
> Ensure you have Python installed beforehand.


## SkyUID_Duplicate_Checker.py

> [!NOTE]
> 
> It will scan all dumps in the main directory, including those in subfolders, and generate a list of dumps with duplicate UIDs.


### Example:

```
Scanning directory and subdirectories from: D:\Skylanders Ultimate NFC Pack\Dumps

Duplicate 4-byte HEX sequences found:

HEX: FC E4 24 29 - Found in files:
  4. Trap Team\9) Traps\1) Crystal Traps\Dark\Dark Spider (Shadow Spider).dump
  4. Trap Team\9) Traps\3) Trappable Villains\Dark\Tae Kwon Crow.dump
HEX: B6 0F DD 9D - Found in files:
  4. Trap Team\9) Traps\1) Crystal Traps\Dark\Dark Sword (Dark Dagger).dump
  4. Trap Team\9) Traps\3) Trappable Villains\Dark\Eye Scream.dump
  4. Trap Team\9) Traps\3) Trappable Villains\Dark\Fisticuffs.dump
  4. Trap Team\9) Traps\3) Trappable Villains\Dark\Nightshade (Doom Raider).dump
HEX: 90 E4 FA 2C - Found in files:
  4. Trap Team\9) Traps\1) Crystal Traps\Earth\Earth Handstand (Rubble Trouble).dump
  4. Trap Team\9) Traps\3) Trappable Villains\Earth\Tussle Sprout.dump
HEX: 6D 6B 35 4B - Found in files:
  4. Trap Team\9) Traps\1) Crystal Traps\Earth\Earth Hourglass (Dust of Time).dump
  4. Trap Team\9) Traps\3) Trappable Villains\Earth\Chomp Chest.dump
HEX: DF 25 B6 4A - Found in files:
  4. Trap Team\9) Traps\1) Crystal Traps\Fire\Fire Scepter (Fire Flower).dump
  4. Trap Team\9) Traps\3) Trappable Villains\Fire\Chef Pepper Jack (Doom Raider).dump
  4. Trap Team\9) Traps\3) Trappable Villains\Fire\Smoke Scream.dump
...
```

## SkyUID_Finder.py

> [!NOTE]
> 
> Enter a UID that you suspect belongs to a Skylander dump file, and the script will identify the corresponding Skylander if it matches.
> 
> For example, the UID `90377C9F` corresponds to the Bash dump file.

### Example:

```
Scanning directory and subdirectories from:

D:\Skylanders Ultimate NFC Pack\Dumps

Enter a 4-byte UID (or type 'exit' to quit): 90377C9F

The UID 90377C9F was found in the following file(s):
  1. Spyro's Adventure\1) Figures\Bash.dump
```

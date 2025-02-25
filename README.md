# ProjectOwls
Think Mega Man bosses, but with a boxer. Made for DMG and Game Gear. It aims to run on original hardware and uses MBC5 (for DMG).

# Controls

| Button Game Boy | Button Game Gear | Action |
|---|---|---|
| Directional Pad |  Joypad | Move Character |
| A | 2 | Jump |
| B | 1 | Attack |
| Up + B | Up + 1 | Special Attack |

# Compile
Adjust paths to GDBK and your favourite emulator if necessary and run the make file or `compile.bat`. You can use `compile.bat -nostart` To just compile the game.

I have not modified the *makefile* for Game Gear support. If you want to compile for that platform, either use the `.bat` file or update the makefile yourself.

## Parameters
```
compile.bat [-nostart]
compile.bat [-nostartgb] [-nostartgg]

-nostart : Don't start any emulator, combines -nostartgb and -nostartgg
-nostartgb: Don't start DMG emulator
-nostartgg: Don't start GG emulator

```

## Frameworks
Made with [GBDK 2020 version 4.3.0](https://github.com/gbdk-2020/gbdk-2020)

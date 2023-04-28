# Code Chaos

A custom gamemode for Mario Parties 1-7 written by [DarkSpine](https://www.youtube.com/channel/UCMPgkBOg8j14q1e4KKe3xkg) and [EndangeredNayla](https://www.youtube.com/channel/UCwTcz4cUVBZ3HAyPJJcbmlw)

## Instructions for patching 
1. Open the folder containing the game you want to patch.
2. Place the .Z64 (Mario Parties 1-3) or .ISO (Mario Party 4-7) inside the folder
3. Run the build.bat. (game will be located in the bin/ folder)

## Playing the game

### Mario Parties 1-3
#### Real Hardware

1. Place the expansion pak inside the Nintendo 64. (yes it is required)
2. Place the ROM onto an Everdrive or 64Drive SD-Card.
3. Boot the game.

#### Mupen64 (using [RMG](https://github.com/Rosalie241/RMG))
1. Download and Install [RMG](https://github.com/Rosalie241/RMG/releases)
2. Place the ROM into the Games folder that RMG reads.
3. Right Click the Game > Edit Game Settings > Core and check Override Game Settings 
   - Set the CPU Emulator to Pure Interperter
4. Right Click the Game > Edit Game Settings > Game
   - Set Memory Size to 8MB
   - Save Type to 16KB EEPROM (for Mario Party 3 only)
5. Boot the game.
  
#### Project64 3
1. Download and Install [Project64](https://www.pj64-emu.com/public-releases)
2. Place the ROM into the Games folder that Project64 reads.
3. Options > Configuration
   - Uncheck Hide Advanced Settings
3. Right Click the Game > Edit Game Settings
   - Set the Memory Size to 8MB
   - Save Type to 16KB EEPROM (for Mario Party 3 only)
4. Right Click the Game > Edit Game Settings > Recompiler
   - Set the CPU Core Style to Interpreter
5. Boot the game.

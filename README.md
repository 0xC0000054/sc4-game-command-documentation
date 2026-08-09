# sc4-game-command-documentation

Documentation for the SimCity 4 game command system.
The game exposes these commands through Lua Test Scripts, a HTTP/TCP socket listener (disabled by default), and the in-game cheat code box.

## Maxis Commands

These commands are present in the base game. 

[App Commands](https://github.com/0xC0000054/sc4-game-command-documentation/tree/main/commands/Maxis/AppCommands.md) - these are available in both the region and city views.    
[City Commands](https://github.com/0xC0000054/sc4-game-command-documentation/tree/main/commands/Maxis/CityCommands.md) - these are available in the city view.    
[Region Commands](https://github.com/0xC0000054/sc4-game-command-documentation/tree/main/commands/Maxis/RegionCommands.md) - these are available in the region view.    

## 3rd-party Commands

This section is reserved for documenting commands added by DLL plugins.

# Using the Commands

## Lua Test Scripts

These scripts are executed -LuaScript command line argument. My [Lua Test Script repository](https://github.com/0xC0000054/sc4-lua-test-scripts) provides example scripts.

## HTTP/TCP Socket

The HTTP/TCP socket listener must first be enabled using the `-NetCommandGenerator:enabled` command line argument when starting the game.
Once enabled the game will listen on port 50020 for connections.

## In-Game Cheat Box

Commands can be entered into the in-game cheat box, but it will discard any output the command produces.

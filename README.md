# BiggerLobby

Removes the 4 player party limit in **Roadside Research**, allowing up to 12 players in a single lobby.

## Installation

Install via [Thunderstore Mod Manager](https://www.overwolf.com/app/Thunderstore-Thunderstore_Mod_Manager) or manually:

1. Download and extract the zip.
2. Place `BepInEx/plugins/BiggerLobby.dll` into your game's `BepInEx/plugins/` folder.
3. Launch the game.

## How It Works

Intercepts `FusionConnection.LaunchAsMultiplayer()` with a Harmony prefix patch and sets `MaxPlayers` to `12` before the lobby is created. No game files are modified.

## Requirements

- BepInEx 6 (IL2CPP)

## Source

[github.com/christianOrona/roadside-research-biggerlobby](https://github.com/christianOrona/roadside-research-biggerlobby)

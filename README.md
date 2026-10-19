# Loader

A lightweight, open-source script for Roblox.

## Usage

Run the following code to use the loader:

```lua
loadstring(game:HttpGet("(https://raw.githubusercontent.com/cookieys/loader/refs/heads/main/Loader.lua)", true))()
```

Features
 * Auto Script Detection: Automatically loads the correct script for your game's Place ID.
 * Error Handling: Ensures smooth execution.
 * Easy Updates: Add new games by editing Games.lua.
Adding New Games
 * Open Games.lua.
 * Add a new entry with the Place ID and script URL:
local Games = {
    [PLACE_ID_HERE] = "URL_TO_SCRIPT.lua",
}

Open Source
This project is open source and contributions are welcome! Feel free to fork the repository, submit pull requests, or report issues.
License
Licensed under the MIT License.
Author
Made with ♡ by XyraV

# Loader

Loader for my hub.

## Usage

Execute:
```lua
pcall(function()
    loadstring(game:HttpGet("[https://raw.githubusercontent.com/cookieys/loader/refs/heads/main/Loader.lua](https://raw.githubusercontent.com/cookieys/loader/refs/heads/main/Loader.lua)"))()
end)
```

Description
Dynamically loads and executes game-specific scripts based on Place ID.
Features
 * Dynamic script loading.
 * Error handling.
 * Extensible via Games.lua.
Adding New Games
Edit Games.lua:
local Games = {
    -- [EXISTING_ID] = "EXISTING_URL",
    [PLACE_ID] = "SCRIPT_URL",
}

License
MIT License. See [LICENSE](https://mit-license.org).
Contributing
Pull requests welcome.
Author
Made with ♡ by XyraV


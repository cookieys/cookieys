# Loader

Loader for my hub.

## Usage

To use this loader, simply execute the following Lua code:

```lua
pcall(function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/cookieys/loader/refs/heads/main/Loader.lua", true))()
end)
```

## Description

This loader is designed to dynamically load and execute scripts based on the current game's Place ID. It fetches a list of game-specific scripts from a remote URL and executes the appropriate script for the game you are currently playing.

## Features

- **Dynamic Script Loading**: Automatically loads the correct script for the current game's Place ID.
- **Error Handling**: Includes robust error handling to ensure smooth execution.
- **Extensible**: Easily add new games and scripts by updating the `Games.lua` file.

## Adding New Games

To add a new game, follow these steps:
1. Open the `Games.lua` file.
2. Add a new entry in the `Games` table with the game's Place ID and the corresponding script URL.

Example:
```lua
local Games = {
    -- Existing game entries...

    -- New Game
    [PLACE_ID_HERE] = "URL_TO_SCRIPT_HERE.lua",
}
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

## Author

Made with ♡ by [XyraV](https://github.com/cookieys)

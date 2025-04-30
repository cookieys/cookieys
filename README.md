# Loader

A dynamic loader for scripts tailored to the game you are playing.

## Usage

To use this loader, execute the following code in your environment:

```lua
pcall(function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/cookieys/loader/refs/heads/main/Loader.lua"))()
end)
```

## Description

This loader dynamically fetches and executes scripts based on the current game's **Place ID**. It uses a centralized list of game-specific scripts hosted remotely, ensuring the correct script is always executed for the game you are playing.

## Features

- **Dynamic Script Loading**: Automatically identifies and loads the appropriate script for the current game's Place ID.
- **Robust Error Handling**: Ensures smooth execution by gracefully handling errors.
- **Easily Extensible**: Add support for new games by updating the `Games.lua` file.

## Adding New Games

To add support for a new game, follow these steps:

1. Open the `Games.lua` file in your project.
2. Add a new entry to the `Games` table with the game's Place ID and the corresponding script URL.

Example:
```lua
local Games = {
    -- Existing game entries...

    -- New Game Entry
    [PLACE_ID_HERE] = "URL_TO_SCRIPT_HERE.lua",
}
```

## License

This project is licensed under the [MIT License](https://mit-license.org/). See the LICENSE file for additional details.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to:
- Open an issue
- Submit a pull request

Your input is appreciated and helps make this project better.

## Author

Made with ♡ by [XyraV](https://github.com/cookieys)

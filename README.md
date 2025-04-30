# Loader

A lightweight, open-source loader for game-specific scripts.

## Usage

Run the following code to use the loader:

```lua
pcall(function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/cookieys/loader/refs/heads/main/Loader.lua"))()
end)
```

## Features

- **Auto Script Detection**: Automatically loads the correct script for your game's Place ID.
- **Error Handling**: Ensures smooth execution.
- **Easy Updates**: Add new games by editing `Games.lua`.

## Adding New Games

1. Open `Games.lua`.
2. Add a new entry with the Place ID and script URL:

```lua
local Games = {
    [PLACE_ID_HERE] = "URL_TO_SCRIPT.lua",
}
```

## Open Source

This project is open source and contributions are welcome! Feel free to fork the repository, submit pull requests, or report issues.

## License

Licensed under the [MIT License](https://mit-license.org/).

## Author

Made with ♡ by [XyraV](https://github.com/cookieys)

## Dependencies

* [`television`](https://github.com/alexpasmantier/television)

## Installation

```sh
ya pkg add cap153/tv
```

## Usage

> [Warning]
> I only tested the built-in `files` and `text` Channels

Add this to your `~/.config/yazi/keymap.toml`:

```toml
[[mgr.prepend_keymap]]
on  = "<C-t>"
run = "plugin tv"
desc = "Jump to a file via tv"

[[mgr.prepend_keymap]]
on  = "<C-t>"
run = "plugin tv text"
desc = "Open files using neovim and jump to where the string is located"
```

## License

This plugin is MIT-licensed. For more information check the [LICENSE](LICENSE) file.

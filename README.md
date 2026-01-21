## 日本語はこちら: [README.ja.md](README.ja.md)

# Ghostty Configuration

Personal configuration for [Ghostty](https://ghostty.org/) terminal emulator.

## Setup

**[IMPORTANT]** on macOS, the default path is `~/Library/Application Support/com.mitchellh.ghostty/config`. To use `~/.config/ghostty/config` which is where this repository makes the config file instead, delete the default config:

```bash
rm ~/Library/Application\ Support/com.mitchellh.ghostty/config
```

To check if Ghostty is reading your config correctly:

```bash
ghostty +show-config
```

## Features

### Appearance
- Font size: 18
- Theme: Tomorrow Night
- Cursor style: Block
- Mouse hides while typing
- Display P3 color space

### Keybindings

| Keybind | Action |
|---------|--------|
| `Shift+Enter` | Insert newline |
| `Alt+Backspace` / `Shift+Backspace` | Delete word |
| `Shift+Delete` | Delete all text |
| `Ctrl+H/J/K/L` | Navigate panes (vim-style) |
| `Ctrl+Shift+V` | Split pane right |
| `Ctrl+Shift+H` | Split pane down |
| `Ctrl+X` | Close pane |
| `Ctrl+,` / `Ctrl+.` | Resize pane left/right |
| `Ctrl+;` / `Ctrl+'` | Resize pane down/up |
| `Ctrl+Shift+K/J` | Scroll up/down  |

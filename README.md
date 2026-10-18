# ghostty-config

Ghostty configuration for macOS, with Catppuccin themes and tmux in mind.

Catppuccin Latte/Mocha switch with light/dark mode. Menlo at 14 pt, a solid background and small window padding.
Windows, a dropdown terminal and shortcuts for tmux.

- `Cmd+N`: new window; `Cmd+Q`: close window; `Cmd+Option+Q`: quit.
- `Cmd+backtick`: toggle the dropdown terminal.
- `Cmd+Shift+H/L`: send tmux's previous/next-window keys (Ctrl+B, then p/n).
- `Cmd+Shift+R`: reload; `Cmd+Shift+P`: command palette.

Back up your current config, then run from this repo:

```sh
mkdir -p ~/.config/ghostty
cp config ~/.config/ghostty/config
```

Reload with `Cmd+Shift+R` (Ghostty → Reload Configuration).

MIT. See [LICENSE](LICENSE).

<div align="center">

# Leenium Hyprlock

<img src="./assets/icon.png" width="120" alt="Leenium Hyprlock logo" />

**A Hyprlock lock screen theme built from the shared Leenium palette.**

Hosted under `github.com/drunkleen/leenium.hyprlock`.

<img src="./assets/preview.png" width="100%" alt="Leenium Hyprlock preview" />

</div>

---

## Features

- **Shared palette** - matches the same Leenium colors used across the other repos
- **Dark lock UI** - restrained borders, centered typography, and soft palette surfaces
- **State colors** - battery and action states use the Leenium accent colors
- **Custom backdrop** - uses a rendered Leenium lock background image

---

## Install

Copy the config and helper files into your Hyprlock config directory:

```bash
git clone https://github.com/drunkleen/leenium.hyprlock.git && cd leenium.hyprlock
mkdir -p ~/.config/hypr/hyprlock
cp hyprlock.conf ~/.config/hypr/hyprlock.conf
cp -r hyprlock/* ~/.config/hypr/hyprlock/
```

---

## Use

- `hyprlock.conf` is the main config file.
- `hyprlock/leenium-hyprlock.png` is the lock backdrop.
- `hyprlock/battery-status-hyprlock` renders the battery line.
- `hyprlock/hyprlock-yubikey-hint` renders the YubiKey hint.

---

## Notes

- The clock, battery, and action labels are all mapped to the shared palette.
- The background is intentionally dark to keep the lock screen low-glare.

---

## The Leenium Ecosystem

Leenium is a unified dark desktop environment built around the same color palette. Alongside this Waybar theme, the project ships matching configs for:

- [**Firefox**](github.com/drunkleen/leenium.firefox) - browser theme extension
- [**Ghidra**](github.com/drunkleen/leenium.ghidra) - reverse engineering framework theme
- [**Limine**](github.com/drunkleen/leenium.limine) - BootLoader
- [**Neovim**](github.com/drunkleen/leenium.nvim) - syntax highlights and UI elements
- [**Omarchy**](github.com/drunkleen/leenium.omarchy) - desktop theme bundle
- [**OpenCode**](github.com/drunkleen/leenium.opencode) - terminal-first theme
- [**VS Code**](github.com/drunkleen/leenium.vscode) - editor theme and UI palette
- [**Waybar**](github.com/drunkleen/leenium.waybar) - editor theme and UI palette

Visit [github.com/drunkleen](https://github.com/drunkleen) or [leenium.drunkleen.com](https://leenium.drunkleen.com/) to explore the full setup.

---

## License

MIT © [Leenium](LICENSE)

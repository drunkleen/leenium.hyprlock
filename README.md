<div align="center">

<img src="https://raw.githubusercontent.com/drunkleen/leenium.webpage/refs/heads/master/assets/LEENIUM.png" width="250" alt="Leenium logo" />

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

<img src="https://raw.githubusercontent.com/drunkleen/leenium.webpage/refs/heads/master/assets/footer.png" width="100%" alt="Leenium footer" />

<p align="center">
    Copyright &copy; 2026-present <a href="https://github.com/drunkleen" target="_blank">LEENIUM</a>
</p>
<p align="center">
    <a href="https://github.com/drunkleen/leenium.webpage/blob/master/LICENSE">
        <img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=365156&colorB=33B8A8"/>
    </a>
</p>

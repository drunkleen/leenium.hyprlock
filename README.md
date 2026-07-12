<div align="center">

# Leenium Hyprlock

<img src="./assets/icon.png" width="120" alt="Leenium Hyprlock logo" />

**A Hyprlock lock screen theme built from the shared Leenium palette.**

Hosted under `github.com/drunkleen/leenium.hyprlock`.

<img src="./assets/preview.png" width="100%" alt="Leenium Hyprlock preview" />

</div>

---

## Color Palette

| Role | Hex | Swatch |
|---|---|---|
| Background | `#0b1113` | ![](https://placehold.co/16x16/0b1113/0b1113.png) |
| Panel | `#11191c` | ![](https://placehold.co/16x16/11191c/11191c.png) |
| Floating | `#182326` | ![](https://placehold.co/16x16/182326/182326.png) |
| Border | `#223033` | ![](https://placehold.co/16x16/223033/223033.png) |
| Active Border | `#304144` | ![](https://placehold.co/16x16/304144/304144.png) |
| Foreground | `#d8e3e0` | ![](https://placehold.co/16x16/d8e3e0/d8e3e0.png) |
| Soft Text | `#a4b4b2` | ![](https://placehold.co/16x16/a4b4b2/a4b4b2.png) |
| Cyan | `#59d6c5` | ![](https://placehold.co/16x16/59d6c5/59d6c5.png) |
| Teal | `#33b8a8` | ![](https://placehold.co/16x16/33b8a8/33b8a8.png) |
| Yellow | `#d9c76b` | ![](https://placehold.co/16x16/d9c76b/d9c76b.png) |
| Blue | `#5e9bff` | ![](https://placehold.co/16x16/5e9bff/5e9bff.png) |
| Emerald | `#4dba7a` | ![](https://placehold.co/16x16/4dba7a/4dba7a.png) |
| Red | `#e16f73` | ![](https://placehold.co/16x16/e16f73/e16f73.png) |

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

## License

MIT © [Leenium](LICENSE)

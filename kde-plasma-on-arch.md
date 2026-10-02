# KDE Plasma on Arch Linux

KDE Plasma is a feature-rich and flexible desktop environment that works well as a daily driver on Arch Linux.

## Why KDE Plasma
- Familiar workflow for users coming from Windows
- Highly customizable without forcing a specific layout
- Good balance between performance and features


## Install

```bash
sudo pacman -S plasma sddm
```
## Display manager

KDE Plasma doesn't include one by default. SDDM is the common pairing:

```bash
sudo systemctl enable sddm --now


## Usage Notes
- Suitable for modern and mid-range hardware
- Stable enough for long-term daily use

Full setup guide:
https://www.musabase.com/2025/12/install-kde-plasma-on-arch-linux.html

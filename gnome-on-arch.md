# GNOME on Arch Linux

GNOME provides a clean and opinionated desktop experience focused on simplicity and consistency.

## Why GNOME
- Clean and distraction-free interface
- Extension-based customization
- Consistent workflow across applications



## Install

```bash
sudo pacman -S gnome gdm
```
## Display manager

GNOME doesn't include one by default. GDM is the common pairing:

```bash
sudo systemctl enable gdm --now
```

## Usage Notes
- Best for users who prefer minimal tweaking
- Works well on modern systems

Full setup guide:
https://www.musabase.com/2026/01/install-gnome-arch-linux.html

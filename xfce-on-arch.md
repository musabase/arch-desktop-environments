# XFCE on Arch Linux

Lightweight, traditional desktop environment. Good choice for older hardware or anyone who wants a stable, low-overhead setup without chasing the latest visual trends.

## Install

```bash
sudo pacman -S xfce4 xfce4-goodies
```

`xfce4-goodies` pulls in the extra plugins and utilities most people actually want, screenshot tool, archive manager, power manager, not strictly required but worth it.

## Display manager

XFCE doesn't include one by default. LightDM is the common pairing:

```bash
sudo pacman -S lightdm lightdm-gtk-greeter
sudo systemctl enable lightdm.service
```

## Notes

- No compositor is enabled out of the box, screen tearing is common until you turn on XFWM's built-in compositor in Window Manager Tweaks
- Panel layout resets to default on first login, expected, not a bug

Full setup guide: https://www.musabase.com/2026/01/install-xfce-on-arch-linux.html

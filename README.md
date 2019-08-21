# Puzzle Bobble Grub2 Theme
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![GPL Licence](https://badges.frapsoft.com/os/gpl/gpl.png?v=103)](https://opensource.org/licenses/GPL-3.0/)

A Simple Puzzle Bobble theme for GRUB2

If you like this theme, please [![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Z8Z511SOI)

![screenshot](https://raw.githubusercontent.com/Luca1991/Puzzle-Bobble-Grub2-Theme/master/screenshot.png)

# Installation

- Clone this repository and copy the **puzzle-bobble folder** to **/boot/grub/themes/**
- Edit **/etc/default/grub** and add or modify the *GRUB_THEME* parameter like this:
```bash
GRUB_THEME="/boot/grub/themes/puzzle-bobble/theme.txt"
```
- Update your grub configuration using this command:
```bash
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

# Tips

- Suggested Grub2 resolution: 1920x1080

# Bugs

If you found a bug, feel free to open an issue or send a PR :)

### Developed with ❤ by Luca D'Amico


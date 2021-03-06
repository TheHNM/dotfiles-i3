# thehnm's Dotfiles

This dotfile repository contains configuration files for my Arch Linux setup with
[dwm](https://github.com/thehnm/dwm).

Furthermore, my Arch Linux installation script [autoarch](https://github.com/thehnm/tarbs)
also installs my configurations found here.
Just download and run it with:

```bash
curl -LO https://raw.githubusercontent.com/thehnm/tarbs/master/install.sh
bash install.sh
```

## Required Sofware

You can find the software with my own changes, configurations and patches here:

- [dwm](https://github.com/thehnm/dwm)
- [dmenu](https://github.com/thehnm/dmenu)
- [st](https://github.com/thehnm/st)
- [slock](https://github.com/thehnm/slock)

## Configuration

This repository contains configuration files for the following software:

- dwm: window manager
- st: terminal
- slock: screen locker
- dmenu
- dunst: notification daemon
- fontconfig
  - Serif: 'Linux Libertine'
  - Sans-Serif: 'Linux Biolinum'
  - Sans: 'Linux Biolinum'
  - Monospace: 'Fira Mono'
  - Non-Latin: 'Noto CJK fonts'
- mpd: Music Player daemon
- ncmpcpp: mpd client
- nvim: Fork of vim
- ranger: Terminal file manager
- sxhkd: simple X hotkey daemon
- youtube-dl: CLI youtube video downloader
- zathura: PDF reader
- zsh
- zsh Plugins, managed by [antibody](https://github.com/getantibody/antibody)
  - [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
  - [zsh-history-substring-search](https://github.com/zsh-users/zsh-history-substring-search)
  - [zsh-completions](https://github.com/zsh-users/zsh-completions)
  - [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)

## Hotkeys

  | Keybinding            | Effect                        |
  | --------------------- | ----------------------------- |
  | F1                    | Display all hotkeys           |
  | Alt + Return          | Open Terminal                 |
  | Alt + p               | Open dmenu program launcher   |
  | Alt + d               | Open passmenu                 |
  | Alt + Shift + d       | Clear Clipboard               |
  | Alt + Shift + q       | Open exit wizard              |
  | Alt + x               | Lock screen with slock        |
  | Alt + Shift + l       | Toggle mpc                    |
  | Alt + Shift + j       | mpc next song                 |
  | Alt + Shift + k       | mpc previous song             |
  | Super + Shift + l     | Toggle playerctl              |
  | Super + Shift + j     | playerctl next song           |
  | Super + Shift + k     | playerctl previous song       |
  | Alt + s               | Display song information      |
  | Alt + o; b            | Open default browser          |
  | Alt + o; m            | Open neomutt                  |
  | Alt + o; v            | Open virt-mananger frontend   |
  | Alt + o; n            | Open ncmpcpp                  |
  | Alt + o; r            | Open newsboat                 |
  | Print                 | Take screenshot               |

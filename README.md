# WARNING! I NO LONGER USE THESE DOTFILES.
## UP TO DATE REPO: [here](https://github.com/witchfuneral/dotfiles)
THIS REPO STILL EXISTS FOR ARCHIVAL PURPOSES.

<h1 align="center">dotfiles</h1>

![screenshot](https://raw.githubusercontent.com/dyingwillow/dotfiles/main/assets/dotfiles.png)

- distro: [arch linux](https://archlinux.org/)
- window manager: [swayfx](https://github.com/WillPower3309/swayfx)
- top bar: [waybar](https://github.com/Alexays/Waybar)
- launcher: [rofi](https://github.com/davatorium/rofi)
- file manager: [pcmanfm](https://archlinux.org/packages/extra/x86_64/pcmanfm-gtk3/)
- terminal emulator: [kitty](https://sw.kovidgoyal.net/kitty/)
- shell: [zsh](https://www.zsh.org/) + [oh-my-zsh](https://ohmyz.sh/)
- editor: [visual studio code](https://github.com/microsoft/vscode)
- font: [iosevka nerd](https://github.com/ryanoasis/nerd-fonts)
- *fetch: [hyfetch](https://github.com/hykilpikonna/hyfetch)
- color palette: [catppuccin mocha](https://github.com/catppuccin/catppuccin)

## Dependencies

- [swayfx](https://aur.archlinux.org/packages/swayfx)
- swaync
- swaybg
- [sway-screenshot](https://aur.archlinux.org/packages/sway-screenshot)
- python-pywal
- waybar
- kitty
- pcmanfm-gtk3
- polkit-gnome
- xdg-desktop-portal & xdg-desktop-portal-wlr
- gnome-keyring

# Optional
- [feishin-bin](https://aur.archlinux.org/packages/feishin-bin)
- flatpak
- [telegram](https://desktop.telegram.org/)
- steam

# Installation

after installing the dependencies and the optional programs, just copy everything in the dotfiles folder to the ~/.config directory.

```
$ git clone https://github.com/dyingwillow/dotfiles

$ cd dotfiles

$ cp -r * ~/.config/ 
```

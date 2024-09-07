# My dotfiles

ovb these are my beaut dots 😊

### Requirements

sudo pacman -S git

sudo pacman -S --needed base-devel git
sudo pacman -S --needed git base-devel && git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si

yay -S tuckr-git

##### The actual programs 
sudo pacman -S hyprland niri foot

yay -S tofi

### Configured Applications
- [X] hyprland
- [X] niri
- [X] tofi
- [ ] hyprpaper
- [X] foot
- [ ] obsidian 

## Instalation

First clone the repo into your ~/.dotfiles/

```
$ git clone https://github.com/MaezrFulldive/dots.git
$ cd .dotfiles
```

then use tuckr to create symlinks 

```
$ tuckr add \*
```

## Refrence
for further info on how this was achieved, and for you to refrence, here is the tuckr repo: https://github.com/RaphGL/Tuckr





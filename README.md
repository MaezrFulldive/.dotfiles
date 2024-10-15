# My dotfiles

obv these are my beaut dots 😊

### Requirements
```
sudo pacman -S git

sudo pacman -S --needed base-devel git
sudo pacman -S --needed git base-devel && git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si

yay -S tuckr-git bat 
```

##### The actual programs 
```
sudo pacman -S hyprland niri foot keepassxc 

yay -S tofi zsh
```

### Configured Applications
- [X] hyprland
- [X] niri
- [X] tofi
- [ ] hyprpaper
- [X] foot
- [ ] obsidian 
- [x] Code-OSS
- [x] zsh

## Instalation

Install zsh
```
$sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

Clone the repo into ~/.dotfiles
```
$ git clone https://github.com/MaezrFulldive/dots.git
$ cd .dotfiles
```

Then use tuckr to create symlinks 

```
$ tuckr add \*
```

To add more dotfiles to your git repo, simple cut and paste the files useing the directory stucture of 

.dotfiles/Configs/your-label/.config/application/dotfile.conf

commit the changes

Then update your local tuckr

```
$ tuckr status

$ tuckr add \*
```

## Refrence
for further info on how this was achieved, and for you to refrence, here is the tuckr repo: https://github.com/RaphGL/Tuckr





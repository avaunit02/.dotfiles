# .config

```
sudo pacman -Syu git
cd $HOME
git clone --recurse-submodules https://github.com/avagordon01/.config
cd .config
sudo pacman -Syu $(cat pkglist.txt)
stow bash
yay -S $(cat aurpkglist.txt)
```

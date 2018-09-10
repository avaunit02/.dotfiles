# paddygords' dotfiles

```
sudo pacman -Syu git
cd $HOME
git clone https://github.com/paddygord/.dotfiles
cd .dotfiles
sudo pacman -Syu $(cat pkglist.txt)
stow */
```

# dotfiles

### ZSH setup:
```
apt install zsh
chsh -s $(which zsh)
```
### Install extra packages:
```
apt install fzf fd-find
```
### Create chezmoi config:
`~/.config/chezmoi/chezmoi.toml`:
```
[data]
    email = "kachkov98@gmail.com"
    name = "Sergey Kachkov"
```
### Install dot files:
```
sh -c "$(curl -fsLS https://get.chezmoi.io)" -- init --apply https://github.com/kachkov98/dotfiles.git
```

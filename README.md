# dotfiles
dotfiles for my NixOS system. This was initially set up for Hyprland and KDE Plasma.

## Setup
At the root of this repo, run:
```bash
stow -t ~/.config .config`
ln -sf ~/github/dotfiles/configuration.nix /etc/nixos/configuration.nix
```

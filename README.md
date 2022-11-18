# LeftWM Catpuccin Setup

## Machine details

- Name: Main Workstation
- Motherboard: ASUS Prime B250-Plus
- CPU: Intel Core i5-7400 (quad-core)
- GPU: AMD Radeon RX 6500 XT
- RAM: 8 GB
- Disk 1: 256GB SSD drive
- Disk 2: 457GB HDD drive

## Software details

- Shell: ZSH
- Terminal: Alacritty
- WM: LeftWM
- Bar: Polybar
- Compositor: picom

## Comments

I am honestly astonished by the small amount of files I had to copy over.
I made this rice to replace XMonad. I ❤️ LeftWM.
This is honestly one of my most beautiful rices, worst one is probably my Qubes OS rices, because of how close they were to the defaults.

## Install instructions

```bash
git clone https://github.com/iVacon/leftwm-catppuccin-setup
cd leftwm-catppuccin-setup
cp -r .config ~/.config
cp .zshrc ~/.zshrc

# Download the wallpaper, credit to Louis Coyle, NOT LICENSED UNDER AGPL 3.0
curl https://cdn.dribbble.com/users/13449/screenshots/12078823/media/c6662b0de7365559f79d9eb6088d9527.png > ~/.config/leftwm/catppuccin/wallpaper.png
```

If you don't have the required software:

```bash
sudo pacman -S leftwm polybar alacritty zsh
```


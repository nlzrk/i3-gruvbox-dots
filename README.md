# i3 Gruvbox Dotfiles

Welcome to the repository for my i3 Gruvbox dotfiles! This collection of configuration files and scripts is designed to customize and enhance the i3 window manager with the popular Gruvbox color scheme. Whether you're new to i3 or a seasoned user, these dotfiles provide a great starting point for creating a visually appealing and efficient workflow. 

![gruvi3](https://github.com/Nolzark-Dev/i3-gruvbox-dots/assets/89377971/bfb4b1d7-de95-4df8-8126-5e4acce8cb81)

![gruvlady](https://github.com/Nolzark-Dev/i3-gruvbox-dots/assets/89377971/b532c69e-06a0-417b-ae63-113472815a7a)

## Getting Started
There are a few dependencies you'll need to replicate the images shown above:
- Picom
- i3 
- i3-gaps
- polybar
- alacritty
- httpie
- dmenu
- rofi 
- feh

Disclaimer: The polybar theme and scripts used can be found at: https://github.com/adi1090x/polybar-themes , the polybar dotfiles contained in this repo are the latest up to 14/10/24

## Nerd Fonts (not required)
To install Nerd Fonts for both Polybar and i3, follow this command list:
```
# Make sure you're in .config
cd ~/.config

# Download the fonts
http -d https://github.com/ryanoasis/nerd-fonts/releases/latest/download/FiraCode.zip
http -d https://github.com/ryanoasis/nerd-fonts/releases/latest/download/Hack.zip

# Unzip the files
mkdir Nerd\ Fonts
unzip FiraCode.zip -d Nerd\ Fonts
unzip Hack.zip -d Nerd\ Fonts

# Move the fonts
sudo mv Nerd\ Fonts /usr/share/fonts

# Remove
rm FiraCode.zip
rm Hack.zip
```
Then youre all done with the Nerd Fonts

## Installation

1. Firstly, clone this repository into your home folder.
```
$ git clone https://github.com/Nolzark-Dev/i3-gruvbox-dots.git
```

2. Secondly, move the 'Wallpaper' directory to your home folder
3. Next up, CD into ~/i3-gruvbox-dots
4. Then, copy the files into your .config folder:
```
$ cp -r * ~/.config
```
5. Then you're done! Reload your i3 config to see the results!

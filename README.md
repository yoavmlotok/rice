# Yoav Mlotok's Rice
A linux rice for an Arch Linux system which uses the sway compositor. \
Based on the [Catppuccin](https://catppuccin.com) theme.

## Installation
Ensure you have the required packages:
```
sudo pacman -S stow \
    sway swaybg swayidle swaylock \
    grim wl-clipboard waybar wmenu \
    kitty btop pavucontrol ttf-firacode-nerd
```
Waybar expects 'btop' and 'pavucontrol' to be installed. However, they are not strictly required for it to work and may be substituted with any other applications.

Clone the repository into your dotfiles directory, and run the stow script:
```
git clone https://github.com/yoavmlotok/rice.git
./rice/stowrice
```

That's it! Everything should be linked correctly!

## Usage
When taking a screenshot the image is saved in the clipboard.
Make sure to save it as a file before taking another one or you will lose it.

The [waybar configuration](https://github.com/yoavmlotok/rice/blob/main/waybar/config.jsonc) has explanations on interactions possible with the modules.

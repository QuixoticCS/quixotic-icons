# Quixotic Icons

This is a port of [Quixotic Color Scheme](https://github.com/QuixoticCS) for [Papirus Icon Theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme).

<p align="center"><img width="50%" src="https://raw.githubusercontent.com/QuixoticCS/quixotic-icons/d488f2df1ed38ea03fbbd140c6ea45b29cd205e0/assets/folders.svg?token=AXFBCJBJ3DUEUOOJBRHZPV3C4LKWG"/></p>

## Requirements

Ensure [Papirus Icon Theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) is installed.

## Installation

```sh

# First, clone the repository and change location to the cloned directory:
$ git clone https://github.com/QuixoticCS/quixotic-icons
cd quixotic-icons

# Copy the contents of the src directory to /usr/share/icons/Papirus
sudo cp -r src/* /usr/share/icons/Papirus

# Call the papirus-folders script to set the color of the folders to the desired theme.
./papirus-folders -C [color] --theme [theme]

# quixotic color options: quixotic-red, quixotic-pink, quixotic-green, quixotic-blue, quixotic-purple, quixotic-cyan
# Theme options: Papirus-Dark, Papirus-Light
```

## Applying

Set the `gtk-icon-theme` to the theme the icons were applied to during installation in `~/.config/gtk-3.0/settings.ini`. Example:

```ini
gtk-icon-theme-name=Papirus-Dark # or Papirus-Light
```

or use a GTK theme manager such as [lxappearance](https://github.com/lxde/lxappearance). 

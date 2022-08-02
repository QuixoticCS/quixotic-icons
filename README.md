<h1 align="center">
	<img src="https://github.com/QuixoticCS/.github/blob/main/profile/assets/logo.svg" width="25%" alt="Logo"/><br/>
	Quixotic for <a href="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme)">Papirus</a>
  </h1>
  
<p align="center"><img width="50%" src="https://github.com/QuixoticCS/quixotic-icons/blob/main/assets/folders.svg"/></p>

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

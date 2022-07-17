# EndeavourOS Notes

The repository contains general information for setting up and configuring EndeavourOS.

## pacman Basics

```shell
# Package management
pacman -Ss <package-name> # Search for a package
padman -Si <package-name> # Display information about a package
pacman -Sy <package-name> # Update the package database and install package

# File management
pacman -Fy <file-name>    # Update the package database and search for a file

# System management
pacman -Suy               # Updates all package
```

## Basic Setup

```shell
# Enable NTP
sudo systemctl enable ntpd
sudo systemctl start ntpd

# Add extra packages
sudo pacman -Sy neovim vim tmux htop bmon exa lshw the_silver_searcher gnote
```

# Dotfiles

Dotfiles for i3 using mate desktop tools and dependencies allowing you to keep mate and i3 installed.
Inspired by parrot and archlabs default dotfiles.
By default this script will setup your hostname as transient and randomize your mac address every reboot.

You need to have mate desktop environment installed or install these package:
* blueman-applet
* nm-applet
* mate-calc
* mate-screensaver
* caja
* mate-screenshot
* mate-power-manager
* mate-screensaver
* mate-notification-daemon

Only openSUSE Tumbleweed and Debian Testing are being supported as for now.
In openSUSE there is no diodon package available, you might want to install cliptit and change your i3 config.
It's posible to use Debian Stable. You just need to install i3-gaps package, modify i3 config to include in itself the color scheme and change polybar config.ini to config.

## Usage
Review and run install.sh

## To-Do:
- [x] Script to auto install dependencies based on diffenrent distros
- [ ] Support for more color schemes and a script to change them, currently only nord is available
- [ ] Script to change fonts, currently iosevka is configured
- [ ] Add parameters to install.sh to make verbosity optional and integrate future color scheme and font selector scripts to it.
- [x] Create another branch to make it compatible with lts distributions

## Some credits:
* [github.com/polybar/polybar-scripts](https://github.com/polybar/polybar-scripts)
* [github.com/newmanls/rofi-themes-collection](https://github.com/newmanls/rofi-themes-collection)
* [github.com/jluttine/rofi-power-menu](https://github.com/jluttine/rofi-power-menu)
* [github.com/junegunn/vim-plug](https://github.com/junegunn/vim-plug)
* [github.com/Qubes-Community/Contents/blob/master/docs/privacy/anonymizing-your-mac-address.md](https://github.com/Qubes-Community/Contents/blob/master/docs/privacy/anonymizing-your-mac-address.md)

i3-conf
=======

My personal configuration for i3.


Packages needed
---------------

i3
- i3-wm
- i3lock
- i3status
- j4-dmenu-desktop

Screen manager
- arandr
- redshift

Background manager
- nitrogen

Network manager
- networkmanager network-manager-applet gnome-icon-theme

Terminal
- konsole

Notification
- dunst (and `mkdir ~/.config/dunst && cp /usr/share/dunst/dunstrc ~/.config/dunst/dunstrc`)

Setup
-----

1. Install all the packages needed.
2. Clone this repo inside `~/.config/i3`
   ```
   git clone https://github.com/bameda/i3-conf.git ~/.config/i3
   ```
3. Set i3status configuration
   ```
   mkdir ~/.config/i3status && ln -s ~/.config/i3/i3status.conf ~/.config/i3status/config
   ```

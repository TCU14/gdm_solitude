## Solitude theme for GDM/Gnome Shell
A simple GDM/Shell theme based on the default gnome-shell theme.


## Install instructions: 
1. Open a terminal, cd into the build directory and type "glib-compile-resources gnome-shell-theme.gresource.xml"
2. As root, copy the generated gnome-shell-theme.gresource file to /usr/share/gnome-shell and restart the GDM system service (Reboot or type "systemctl restart gdm")

## Changing the accent color

By default, Solitude uses a shade of red as its accent color. To change the accent color, do the following:

1. Find the hex color code of the new accent color you wish to use. Open gnome-shell.css and find/replace every instance with the hex code of #820000 with the new color you have chosen.
2. Find the rgba color code of the new accent color you wish to use, open gnome-shell.css and find/replace every instance of rgba(130, 0, 0, 1) and replace it with the rgba color code of the new accent color.
3. Recompile gnome-shell-theme.gresource and install it, restart the GDM service.

## Changing the Background-Size property

By default this is set to 2400px by 1600 px. Find background-size inside gnome-shell.css and change it to reflect the size of your display

## Changing the background

Open gnome-shell-theme.gresource.xml and switch out Background.jpg to the new desired background. Recompile and install to test, the background-size property may or may not match the size of the background, usually it matches your display resolution

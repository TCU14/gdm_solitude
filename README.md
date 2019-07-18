## Solitude theme for GDM

Install instructions: 
1. Open a terminal, cd into the build directory and type "glib-compile-resources gnome-shell-theme.gresource.xml"
2. As root, copy the generated gnome-shell-theme.gresource file to /usr/share/gnome-shell and restart the GDM system service (Reboot or type "systemctl restart gdm")

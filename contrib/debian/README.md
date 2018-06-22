
Debian
====================
This directory contains files used to package endorphind/endorphin-qt
for Debian-based Linux systems. If you compile endorphind/endorphin-qt yourself, there are some useful files here.

## endorphin: URI support ##


endorphin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install endorphin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your endorphin-qt binary to `/usr/bin`
and the `../../share/pixmaps/endorphin128.png` to `/usr/share/pixmaps`

endorphin-qt.protocol (KDE)



Debian
====================
This directory contains files used to package bbeed/bbee-qt
for Debian-based Linux systems. If you compile bbeed/bbee-qt yourself, there are some useful files here.

## bbee: URI support ##


bbee-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bbee-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bbeeqt binary to `/usr/bin`
and the `../../share/pixmaps/bbee128.png` to `/usr/share/pixmaps`

bbee-qt.protocol (KDE)


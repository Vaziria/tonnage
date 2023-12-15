
Debian
====================
This directory contains files used to package tonnaged/tonnage-qt
for Debian-based Linux systems. If you compile tonnaged/tonnage-qt yourself, there are some useful files here.

## tonnage: URI support ##


tonnage-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tonnage-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tonnage-qt binary to `/usr/bin`
and the `../../share/pixmaps/tonnage128.png` to `/usr/share/pixmaps`

tonnage-qt.protocol (KDE)


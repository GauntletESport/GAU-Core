
Debian
====================
This directory contains files used to package gauntletd/gauntlet-qt
for Debian-based Linux systems. If you compile gauntletd/gauntlet-qt yourself, there are some useful files here.

## gauntlet: URI support ##


gauntlet-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gauntlet-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gauntlet-qt binary to `/usr/bin`
and the `../../share/pixmaps/gauntlet128.png` to `/usr/share/pixmaps`

gauntlet-qt.protocol (KDE)



Debian
====================
This directory contains files used to package betxoind/betxoin-qt
for Debian-based Linux systems. If you compile betxoind/betxoin-qt yourself, there are some useful files here.

## betxoin: URI support ##


betxoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install betxoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your betxoinqt binary to `/usr/bin`
and the `../../share/pixmaps/betxoin128.png` to `/usr/share/pixmaps`

betxoin-qt.protocol (KDE)


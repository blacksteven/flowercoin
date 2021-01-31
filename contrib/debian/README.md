
Debian
====================
This directory contains files used to package flowercoind/flowercoin-qt
for Debian-based Linux systems. If you compile flowercoind/flowercoin-qt yourself, there are some useful files here.

## flowercoin: URI support ##


flowercoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install flowercoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your flowercoinqt binary to `/usr/bin`
and the `../../share/pixmaps/flowercoin128.png` to `/usr/share/pixmaps`

flowercoin-qt.protocol (KDE)


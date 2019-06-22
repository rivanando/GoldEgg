
Debian
====================
This directory contains files used to package goldeggd/goldegg-qt
for Debian-based Linux systems. If you compile goldeggd/goldegg-qt yourself, there are some useful files here.

## goldegg: URI support ##


goldegg-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install goldegg-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your goldeggqt binary to `/usr/bin`
and the `../../share/pixmaps/goldegg128.png` to `/usr/share/pixmaps`

goldegg-qt.protocol (KDE)


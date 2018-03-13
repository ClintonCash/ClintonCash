
Debian
====================
This directory contains files used to package clintoncashd/clintoncash-qt
for Debian-based Linux systems. If you compile clintoncashd/clintoncash-qt yourself, there are some useful files here.

## clintoncash: URI support ##


clintoncash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install clintoncash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your clintoncash-qt binary to `/usr/bin`
and the `../../share/pixmaps/clintoncash128.png` to `/usr/share/pixmaps`

clintoncash-qt.protocol (KDE)


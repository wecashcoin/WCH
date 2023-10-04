
Debian
====================
This directory contains files used to package wchd/wch-qt
for Debian-based Linux systems. If you compile wchd/wch-qt yourself, there are some useful files here.

## pivx: URI support ##


wch-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install wch-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your wch-qt binary to `/usr/bin`
and the `../../share/pixmaps/wch128.png` to `/usr/share/pixmaps`

wch-qt.protocol (KDE)


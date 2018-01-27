
Debian
====================
This directory contains files used to package Altaird/Altair-qt
for Debian-based Linux systems. If you compile Altaird/Altair-qt yourself, there are some useful files here.

## Altair: URI support ##


Altair-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Altair-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Altairqt binary to `/usr/bin`
and the `../../share/pixmaps/Altair128.png` to `/usr/share/pixmaps`

Altair-qt.protocol (KDE)


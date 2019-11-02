
Debian
====================
This directory contains files used to package leedcoind/leedcoin-qt
for Debian-based Linux systems. If you compile leedcoind/leedcoin-qt yourself, there are some useful files here.

## leedcoin: URI support ##


leedcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install leedcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your leedcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/leedcoin128.png` to `/usr/share/pixmaps`

leedcoin-qt.protocol (KDE)


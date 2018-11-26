
Debian
====================
This directory contains files used to package clycoind/clycoin-qt
for Debian-based Linux systems. If you compile clycoind/clycoin-qt yourself, there are some useful files here.

## clycoin: URI support ##


clycoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install clycoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your clycoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/clycoin128.png` to `/usr/share/pixmaps`

clycoin-qt.protocol (KDE)



Debian
====================
This directory contains files used to package SIQSd/SIQS-qt
for Debian-based Linux systems. If you compile SIQSd/SIQS-qt yourself, there are some useful files here.

## SIQS: URI support ##


SIQS-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install SIQS-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your SIQS-qt binary to `/usr/bin`
and the `../../share/pixmaps/SIQS128.png` to `/usr/share/pixmaps`

SIQS-qt.protocol (KDE)

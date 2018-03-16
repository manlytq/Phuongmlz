
Debian
====================
This directory contains files used to package xeond/xeon-qt
for Debian-based Linux systems. If you compile xeond/xeon-qt yourself, there are some useful files here.

## xeon: URI support ##


xeon-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install xeon-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your xeon-qt binary to `/usr/bin`
and the `../../share/pixmaps/xeon128.png` to `/usr/share/pixmaps`

xeon-qt.protocol (KDE)


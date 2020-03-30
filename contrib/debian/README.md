
Debian
====================
This directory contains files used to package safecrexd/safecrex-qt
for Debian-based Linux systems. If you compile safecrexd/safecrex-qt yourself, there are some useful files here.

## safecrex: URI support ##


safecrex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install safecrex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your safecrex-qt binary to `/usr/bin`
and the `../../share/pixmaps/safecrex128.png` to `/usr/share/pixmaps`

safecrex-qt.protocol (KDE)


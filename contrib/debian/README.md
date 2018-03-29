
Debian
====================
This directory contains files used to package agnid/agni-qt
for Debian-based Linux systems. If you compile agnid/agni-qt yourself, there are some useful files here.

## agni: URI support ##


agni-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install agni-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your agni-qt binary to `/usr/bin`
and the `../../share/pixmaps/agni128.png` to `/usr/share/pixmaps`

agni-qt.protocol (KDE)


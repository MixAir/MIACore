
Debian
====================
This directory contains files used to package miad/mia-qt
for Debian-based Linux systems. If you compile miad/mia-qt yourself, there are some useful files here.

## mia: URI support ##


mia-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mia-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your miaqt binary to `/usr/bin`
and the `../../share/pixmaps/mia128.png` to `/usr/share/pixmaps`

mia-qt.protocol (KDE)



Debian
====================
This directory contains files used to package celerd/celer-qt
for Debian-based Linux systems. If you compile celerd/celer-qt yourself, there are some useful files here.

## celer: URI support ##


celer-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install celer-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your celer-qt binary to `/usr/bin`
and the `../../share/pixmaps/celer128.png` to `/usr/share/pixmaps`

celer-qt.protocol (KDE)


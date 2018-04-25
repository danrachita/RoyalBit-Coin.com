
Debian
====================
This directory contains files used to package robid/robi-qt
for Debian-based Linux systems. If you compile robid/robi-qt yourself, there are some useful files here.

## robi: URI support ##


robi-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install robi-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your robiqt binary to `/usr/bin`
and the `../../share/pixmaps/robi128.png` to `/usr/share/pixmaps`

robi-qt.protocol (KDE)


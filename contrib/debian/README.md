
Debian
====================
This directory contains files used to package vpsd/vps-qt
for Debian-based Linux systems. If you compile vpsd/vps-qt yourself, there are some useful files here.

## vps: URI support ##


vps-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install vps-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vpsqt binary to `/usr/bin`
and the `../../share/pixmaps/vps128.png` to `/usr/share/pixmaps`

vps-qt.protocol (KDE)



Debian
====================
This directory contains files used to package venoxd/venox-qt
for Debian-based Linux systems. If you compile venoxd/venox-qt yourself, there are some useful files here.

## venox: URI support ##


venox-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install venox-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your venoxqt binary to `/usr/bin`
and the `../../share/pixmaps/venox128.png` to `/usr/share/pixmaps`

venox-qt.protocol (KDE)



Debian
====================
This directory contains files used to package wingedd/winged-qt
for Debian-based Linux systems. If you compile wingedd/winged-qt yourself, there are some useful files here.

## winged: URI support ##


winged-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install winged-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your wingedqt binary to `/usr/bin`
and the `../../share/pixmaps/winged128.png` to `/usr/share/pixmaps`

winged-qt.protocol (KDE)


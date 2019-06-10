
Debian
====================
This directory contains files used to package factord/factor-qt
for Debian-based Linux systems. If you compile factord/factor-qt yourself, there are some useful files here.

## factor: URI support ##


factor-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install factor-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your factor-qt binary to `/usr/bin`
and the `../../share/pixmaps/factor128.png` to `/usr/share/pixmaps`

factor-qt.protocol (KDE)


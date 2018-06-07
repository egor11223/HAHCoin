
Debian
====================
This directory contains files used to package hahd/hah-qt
for Debian-based Linux systems. If you compile hahd/hah-qt yourself, there are some useful files here.

## hah: URI support ##


hah-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hah-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hah-qt binary to `/usr/bin`
and the `../../share/pixmaps/hah128.png` to `/usr/share/pixmaps`

hah-qt.protocol (KDE)


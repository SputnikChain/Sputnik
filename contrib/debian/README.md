
Debian
====================
This directory contains files used to package Sputnikd/Sputnik-qt
for Debian-based Linux systems. If you compile Sputnikd/Sputnik-qt yourself, there are some useful files here.

## Sputnik: URI support ##


Sputnik-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Sputnik-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Sputnikqt binary to `/usr/bin`
and the `../../share/pixmaps/Sputnik128.png` to `/usr/share/pixmaps`

Sputnik-qt.protocol (KDE)


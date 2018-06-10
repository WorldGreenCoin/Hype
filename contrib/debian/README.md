
Debian
====================
This directory contains files used to package hyped/hype-qt
for Debian-based Linux systems. If you compile hyped/hype-qt yourself, there are some useful files here.

## hype: URI support ##


hype-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hype-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hypeqt binary to `/usr/bin`
and the `../../share/pixmaps/hype128.png` to `/usr/share/pixmaps`

hype-qt.protocol (KDE)


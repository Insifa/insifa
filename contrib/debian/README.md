
Debian
====================
This directory contains files used to package insifad/insifa-qt
for Debian-based Linux systems. If you compile insifad/insifa-qt yourself, there are some useful files here.

## insifa: URI support ##


insifa-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install insifa-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your insifaqt binary to `/usr/bin`
and the `../../share/pixmaps/insifa128.png` to `/usr/share/pixmaps`

insifa-qt.protocol (KDE)


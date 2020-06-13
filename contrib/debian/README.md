
Debian
====================
This directory contains files used to package logecoind/logecoin-qt
for Debian-based Linux systems. If you compile logecoind/logecoin-qt yourself, there are some useful files here.

## logecoin: URI support ##


logecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install logecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your logecoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

logecoin-qt.protocol (KDE)


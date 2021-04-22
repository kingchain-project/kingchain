
Debian
====================
This directory contains files used to package kingchaind/kingchain-qt
for Debian-based Linux systems. If you compile kingchaind/kingchain-qt yourself, there are some useful files here.

## kingchain: URI support ##


kingchain-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install kingchain-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your kingchainqt binary to `/usr/bin`
and the `../../share/pixmaps/kingchain128.png` to `/usr/share/pixmaps`

kingchain-qt.protocol (KDE)


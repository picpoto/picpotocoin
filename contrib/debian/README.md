
Debian
====================
This directory contains files used to package ppod/ppo-qt
for Debian-based Linux systems. If you compile ppod/ppo-qt yourself, there are some useful files here.

## ppo: URI support ##


ppo-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ppo-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ppoqt binary to `/usr/bin`
and the `../../share/pixmaps/ppo128.png` to `/usr/share/pixmaps`

ppo-qt.protocol (KDE)


# rsmenu

The article describes a simple but handy utility menu for a RPi installation of
radiosonde-auto-rx.

This utility uses a text mode terminal, so access by a SSH terminal session
or a terminal windows if running under a GUI.

This utility uses [shmenu](https://github.com/owenduffy/shmenu/releases). For a
RPi, download and install the latest armhf version.

(Hint: sudo apt install \<package file name>.)

I use a dedicated user radiosonde for radiosonde-auto-rx, and the bulk of
radiosonde-auto-rx is installed in subdirectory /home/radiosonde/radiosonde-auto-rx.
The files below are installed in the user’s root directory.


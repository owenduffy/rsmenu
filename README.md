# rsmenu

The article describes a simple but handy utility menu for a RPi installation of
radiosonde-auto-rx.

This utility uses a text mode terminal, so access by a SSH terminal session
or a terminal windows if running under a GUI.

This utility uses [shmenu](https://github.com/owenduffy/shmenu/releases). For a
RPi, download and install the latest armhf version. (Hint: sudo apt install \<package file name>.)

rsmenu also depends on libncurses5 or libncurses6 which may not be already
installed. If not download and install the latest armhf version: sudo apt-get install libncurses6.

I use a dedicated user radiosonde for radiosonde-auto-rx, and the bulk of
radiosonde-auto-rx is installed in subdirectory /home/radiosonde/radiosonde-auto-rx.
The files below are installed in the user’s root directory.

## EDITOR

The script uses the environment variable EDITOR. If it is not set sensibly then:

- find the path to your preferred editor, eg whereis nano
- at the end of ~/.profile, add this line (modified to suit your own editor)

export EDITOR=/usr/bin/nano

Log off and login again to test it.


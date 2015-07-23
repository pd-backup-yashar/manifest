# How to build

$ mkdir projectdisco
$ cd projectdisco
$ repo init -u https://github.com/ProjectDisco/manifest -b lollipop
$ repo sync -j4
$ . build/envsetup.sh
$ make -j4 disco

# How to build

```bash
$ mkdir projectdisco
$ cd projectdisco
$ repo init -u https://github.com/ProjectDisco/manifest -b marshmallow
$ repo sync -j4
$ . build/envsetup.sh
$ lunch
$ make -j4 disco
```

# Submitting Patches
Patches are always welcome! Feel free to sumbit pull requests to our git.

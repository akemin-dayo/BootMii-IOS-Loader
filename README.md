BootMii IOS Loader
==================
##### A simple BootMii IOS loader.

A simple app that loads the IOS version of BootMii, given that it is installed as IOS254.

Requires devkitPPC and devkitPro to compile.

As with all my Wii projects, the Makefile here has been modified with the following commands:

* `make package` will compile the project, create an HBC-compliant app folder, and create a ZIP file out of it for release.

* `make release` does the same thing, but runs `make clean` before doing anything.

Binaries can be found [here](https://github.com/angelXwind/BootMii-IOS-Loader/releases/).
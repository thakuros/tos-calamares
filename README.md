# tos-calamares
Calamares Installer for Thakur OS
Calamares is a universal installer framwork for Linux distribution. This repository contains Thakur OS specific modules & configurations above the framework.
This repositry contains software which is still under development.

<h2>How to Get TOS-Calamares on your system to test it?</h2>
Clone Calamares from GitHub, run CMake, and compile it:
<code>
$ git clone https://github.com/thakuros/tos-calamares.git
$ mkdir calamares/build
$ cd calamares/build
$ cmake -DCMAKE_BUILD_TYPE=Debug ..
$ make
</code>

This will give you a debug build of Calamares, with debug symbols. It can then be run straight from the build directory without installing in one of the following ways:
<code>
$ ./calamares -d
$ sudo ./calamares -d
$ pkexec ./calamares -d
</code>

This repository is linked to the ThakurOS <a href="https://github.com/thakuros/TOS-pkgbuild/tree/master/calamares">PKGBULD</a> repository. You can visit there to build the installer tarball (in zst format), which will be on the ISO. The forntend branding modules are in the <a href="https://github.com/thakuros/TOS-calamares-config">configurations</a> repository. 

<h3>Screenshot</h3>
<img src="ss.png">

# tos-calamares
Calamares Installer for Thakur OS<br>
Calamares is a universal installer framwork for Linux distribution. This repository contains Thakur OS specific modules & configurations above the framework.<br>
This repositry contains software which is still under development.<br>

<h2>How to Get TOS-Calamares on your system to test it?</h2>
Clone Calamares from GitHub, run CMake, and compile it:
<code>
$ git clone https://github.com/thakuros/tos-calamares.git <br>
$ mkdir calamares/build<br>
$ cd calamares/build<br>
$ cmake -DCMAKE_BUILD_TYPE=Debug ..<br>
$ make<br>
</code>

This will give you a debug build of Calamares, with debug symbols. It can then be run straight from the build directory without installing in one of the following ways:
<code>
$ ./calamares -d<br>
$ sudo ./calamares -d<br>
$ pkexec ./calamares -d<br>
</code>

This repository is linked to the ThakurOS <a href="https://github.com/thakuros/TOS-pkgbuild/tree/master/calamares">PKGBULD</a> repository. You can visit there to build the installer tarball (in zst format), which will be on the ISO. The forntend branding modules are in the <a href="https://github.com/thakuros/TOS-calamares-config">configurations</a> repository. 

<h3>Screenshot</h3>
<img src="ss.png">

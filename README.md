# tos-calamares
Calamares Installer for Thakur OS<br>
Calamares is a universal installer framwork for Linux distribution. This repository contains Thakur OS specific modules & configurations above the framework.
This repository contains software which is still under development.<br>

<h2>How to Get TOS-Calamares on your system to test it?</h2>
Clone Calamares from GitHub, run CMake, and compile it:<br><br>
<code>$ git clone https://github.com/thakuros/tos-calamares.git </code><br>
<code>$ mkdir calamares/build</code><br>
<code>$ cd calamares/build</code><br>
<code>$ cmake -DCMAKE_BUILD_TYPE=Debug ..</code><br>
<code>$ make</code><br>
<br>

This will give you a debug build of Calamares, with debug symbols. It can then be run straight from the build directory without installing in one of the following ways:
<br><br>
<code>$ ./calamares -d</code><br>
<code>$ sudo ./calamares -d</code><br>
<code>$ pkexec ./calamares -d</code><br>


This repository is linked to the ThakurOS <a href="https://github.com/thakuros/TOS-pkgbuild/tree/master/calamares">PKGBULD</a> repository. You can visit there to build the installer tarball (in zst format), which will be on the ISO. The forntend branding modules are in the <a href="https://github.com/thakuros/TOS-calamares-config">configurations</a> repository. 

<h2>Screenshot</h2>
<br>
<img src="ss.png">

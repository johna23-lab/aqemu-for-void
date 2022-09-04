Example how to build using meson/ninja in Linux Void:
```
sudo xbps-install  qt5-devel libvncserver-devel git gcc pkg-config meson
git clone https://github.com/nikitamos/aqemu
cd aqemu
meson builddir
cd builddir
ninja
strip aqemu
./aqemu
```
The release version comes with the segmentation fault fixed, thanks to nikitamos for the fix
https://github.com/nikitamos/aqemu

I set up a [crowdfunding page for AQEMU](https://salt.bountysource.com/teams/aqemu), it will enable users to donate for the whole
project and/or for individual issues. Please consider setting up a monthly donation.

I want AQEMU to pick up steam again with your help, with the goal of making the best
virtual machine manager GUI.

Bountysource crowdfunding page for AQEMU: https://salt.bountysource.com/teams/aqemu

Patreon crowdfunding page: https://www.patreon.com/tobimensch

Donate via PayPal: donate2aqemu@emailn.de


![ScreenShot](https://i.imgur.com/PkvFUEk.png)

Current stable release: https://github.com/tobimensch/aqemu/releases/tag/v0.9.2
See the CHANGELOG for details.

Upgrading from 0.8.2 is highly recommended.

---

Port of AQEMU 0.8.2 from Qt4 to Qt5.

---

Use cmake to build.

Dependencies: 
 - Qt5Core
 - Qt5Widgets 
 - Qt5Network
 - Qt5Test
 - Qt5PrintSupport
 - Qt5DBus
 - LibVNCServer


---

As an alternative to cmake the meson build system is also supported:
https://github.com/mesonbuild/meson


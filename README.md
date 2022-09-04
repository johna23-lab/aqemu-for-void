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
---



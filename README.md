# Plymouth ArtisTech.com OS Loading Screen
Plymouth theme with ArtisTech logo:

![artistech.com](artistech-logo.png)

This is pretty much just the ubuntu-logo theme with the ubuntu-logo.png and ubuntu-logo16.png images replaced by the ArtisTech logo images.

## Install

The value `102` can be any value, it's used in the auto value for `update-alternatives` config.
```sh
sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/artistech/artistech.plymouth 102
sudo update-alternatives --config default.plymouth
sudo update-initramfs -u
sudo reboot
```

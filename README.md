minipro
========
An opensource rewrittement of autoelectric.cn programming utility

## Features
* Compatibility with Minipro TL866CS and Minipro TL866A
* More than 13000 target devices (including AVRs, PICs, various BIOSes and EEPROMs)
* ZIF40 socket and ISP support
* Vendor-specific MCU configuration bits
* Chip ID verification
* Overcurrency protection
* System testing

## Installing under Debian / Ubuntu

Installing from this repository is as easy as:

```nohighlight
sudo apt-get install build-essential libusb-1.0-0-dev fakeroot dpkg-dev
git clone https://github.com/vdudouyt/minipro/ && cd minipro/
fakeroot dpkg-buildpackage -b
sudo dpkg -i ../minipro_0.1-1_i386.deb
```

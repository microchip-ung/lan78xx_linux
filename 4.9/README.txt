readme.txt

lan78xx_linux driver for kernel version 4.9
This driver implemenets the NAPI mechanism.

Building Instructions (Assume that linux kernel build tools are already setup)
- Download 4.9.x kernel source tree for your platform.
- Replace lan78xx.c in /drivers/net/usb/
- Make sure that lan78xx is enabled as a module in your config
- $ sudo make drivers/net/usb/lan78xx.ko
- $ sudo rmmod lan78xx
- $ sudo insmod drivers/net/usb/lan78xx.ko

Version History
V.1.0 The initial NAPI lan78xx driver release for linux kernel 4.9.x
      Tested on 4.9.112


lan78xx Linux driver for kernel version x.x.x.

Building Instructions (Assume that linux kernel build tools are already setup)
- Download kernel source tree of for your platform. Please make sure to download the kernel tree that matches with the driver version.
- Replace lan78xx.c in /drivers/net/usb/
- Make sure that lan78xx is enabled as a module in your config
- $ sudo make drivers/net/usb/lan78xx.ko
- $ sudo rmmod lan78xx
- $ sudo insmod drivers/net/usb/lan78xx.ko

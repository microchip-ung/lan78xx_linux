==============================================================================
Linux Device driver for Microchip LAN78xx
==============================================================================

Contents:

1. Platforms and OS versions supported
2. Device support
3. Driver structure and file description
4. Building and installing the driver

1. Platforms and kernel versions supported
------------------------------------------

- x86/x64 PC

2. Device support
-----------------

This release supports:
  EVB-LAN7801-EDS
	• J11 – Shunt installed between 1 and 2
	• J15 – Shunt installed between 1 and 2
	• J16 – Shunt installed between 1 and 2

3. Driver structure and file description
----------------------------------------

Each directory correspond to a kernel version for which the driver is intended
for.

4. Building and installing the driver
-------------------------------------

Go to the corresponding directory and run the following commands:

To apply the patch: 

git apply <Patchname>

The build command is:

make

The clean command is:

make clean

To install the module:

insmod lan78xx.ko

To remove the module

rmmod lan78xx

Robot-PKGBUILDs
===============

PKGBUILDs for robotics - xenomai canfestival

The ease of creating packaging scripts for Archlinux and setting up binary repos has led me to use it for installing and maintaining software on various robots I've built or used.

Normally I put PKGBUILDs up on AUR but for the xenomai kernels and things that depend on them, it's tricky. Normally xenomai kernels lag behind the bleeding edge and one needs to have a little care when installing one.

Xenomai
-------

Building and installing the xenomai realtime kernel can be a real PITA. The xenomai PKGBUILDs here can be a good starting point.

Presently this is kernel version 3.2.21 with xenomai 2.6.1

RTnet
-----

http://www.rtnet.org/index.html

(from the website) RTnet is an Open Soure hard real-time network protocol stack for Xenomai and RTAI (real-time Linux extensions). It makes use of standard Ethernet hardware and supports several popular NIC chip sets, including Gigabit Ethernet. Moreover, Ethernet-over-1394 support is available based on the RT-FireWire protocol stack.

Etherlabmaster
--------------

Ethercat master


PEAK linux driver
-----------------

Drivers for PEAK CAN bus cards


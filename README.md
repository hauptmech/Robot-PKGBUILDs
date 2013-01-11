Robot-PKGBUILDs
===============

PKGBUILDs for robotics - xenomai canfestival RTnet Etherlabmaster PEAK-Systems

The ease of creating packaging scripts for Archlinux and setting up binary repos has led me to use it for installing and maintaining software on various robots I've built or used.

Normally I put PKGBUILDs up on AUR but for the xenomai kernels and things that depend on them, it's tricky. Normally xenomai kernels lag behind the bleeding edge and one needs to have a little care when installing one.

linux-xenomai
-------

Building and installing the xenomai realtime kernel can be a real PITA. The xenomai PKGBUILDs here can be a good starting point.

Kernels for non-x86 architectures (ARM) have an additional identifier. 

The PKGBUILD creates packages for the kernel, kernel headers, and xenomai itself.

RTnet
-----

http://www.rtnet.org/index.html

(from the website) RTnet is an Open Soure hard real-time network protocol stack for Xenomai and RTAI (real-time Linux extensions). It makes use of standard Ethernet hardware and supports several popular NIC chip sets, including Gigabit Ethernet. Moreover, Ethernet-over-1394 support is available based on the RT-FireWire protocol stack.

Etherlabmaster
--------------

Ethercat master


PEAK linux driver
-----------------

Drivers for PEAK CAN bus cards. Since I'm running mixed kernel versions 
(a la Manjaro linux) I've configured the drivers so they can be installed 
side-by-side for different kernel versions. However, for realtime vs 
non-realtime drivers on the same kernel version you must replace the driver 
via a pacman install.


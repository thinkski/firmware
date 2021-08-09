Nvidia Jetson Nano u-boot binaries
==================================

This directory contains Nvidia Jetson Nano u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://developer.nvidia.com/embedded/jetson-nano>

Source information
-------------
> *Last Update:* Mon 9 Aug 2021 12:31:00 AM PDT

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Thu Jul 29 09:22:02 2021 +0200
  * **GIT Hash:** 3823315cbedf930c52fe77452063ab6d62b157be
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make p3450-0000_defconfig
  * ARCH=arm64 CROSS_COMPILE=aarch64-linux-gnu- make

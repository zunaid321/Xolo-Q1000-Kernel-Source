WHAT IS THIS?
=============

Linux Kernel source code for the device XoloQ1000/SymphonyW140

BUILD INSTRUCTIONS?
===================

First Download the Source code from here :) By Clicking Download Zip or Clone it :)

Build the kernel:
Go to the kernel directory and issue these commands: 
export ARCH=arm
KBUILD_BUILD_HOST=ZunaidLenovoS405
export TARGET_BUILD_VARIANT=user
./makeMtk -t -o=TARGET_BUILD_VARIANT=user eastaeon89_wet_kk n k

After the kernel is compiled , replace the zimage in the boot.img of the current kernel and flash it up :)


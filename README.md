Overview
========
This is linux 0.01 version, which used to learn kernel for newbie
All is tested under ubuntu 12.04 i386, in x64 system building will failed.

Build
=====

    sudo apt-get install bin86, binutils, gcc, qemu
    make # Will create a Image file
    qemu -hdb hd_oldlinux.img -fda Image -boot a # Boot from a floppy

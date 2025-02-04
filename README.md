# HemeshOS  

Please read this before downloading this img file

# step 1 QEMU VM

install it in linux/macOS

linux:

for Ubuntu and Debian-based OS:
 
$ sudo apt install qemu-kvm

Redhat and fedora

$ sudo dnf install qemu

Manjaro and Arch-based:

$ sudo pacman -Sy qemu

For MacOS:

 $ sudo port install qemu

For Windows:
in your browser search qemu Download and select one
next setup install  WSL (Windows Subsystem for Linux)

# Run the OS

on Linux/MacOS

$ sudo qemu-system_x86_64 boot.img -vga cirrus

in windows type:

> sudo qemu-system_x86_64 boot.img -vga cirrus


# Inside The VM


you will see no configration file  found so type:

/bzImage rw root=/dev/sda

and press enter

and wait 



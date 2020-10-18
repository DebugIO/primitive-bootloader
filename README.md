# primitive-bootloader
This is a very simple bootloader and doesn't do anything.

![Bootloader running in QEMU](https://github.com/DebugIO/primitive-bootloader/blob/main/images/bootloader%20running%20in%20qemu.png?raw=true)

# How to compile the bootloader
**You need NASM installed**


**If you're on Windows you also need to add it to the path variable**


Run the **make.bat** script or type this command: `nasm -f bin boot.asm -o boot.bin`

# How to run it in QEMU
Run the **run.bat** script or type this command: `qemu-system-x86_64 boot.bin`

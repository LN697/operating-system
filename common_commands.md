# Common Commands
Create a bootloader file `nasm -f bin bootloader.asm -o bootloader`\
Create a 1.44MB floppy disk image file `dd if=/dev/zero of=disk.img bs=512 count=2880`\
Write bootloader to the first sector `dd conv=notrunc if=bootloader of=disk.img bs=512`
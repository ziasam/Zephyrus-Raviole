Install Instructions

1. Make sure your Bootloader is unlocked and You are coming from latest stock firmware.
2. Connect phone to pc and boot to bootloader.
3. Type fastboot -w in cmd prompt/terminal.
4. Download provided rom.zip, boot.img and vendor_boot.img from release
5. flash vendor_boot.img (fastboot flash vendor_boot vendor_boot.img)
6. flash boot.img (fastboot flash boot boot.img)
7. Boot to recovery.
8. Naviate to Adb sideload option and press sideload.
9. Now from pc type adb sideload rom.zip.
10. After sideloading is complete, format storage and reboot to system.

fastboot Images will be provided with march release.

Install Instruction

(Provided recovery is LineageOS recovery)

1. Make sure your Bootloader is unlocked and You are coming from latest stock firmware.
2. Connect phone to pc and boot to bootloader.
3. Type fastboot -w in cmd prompt/terminal.
4. Download provided rom.zip and vendor_boot.img from release and type (fastboot flash vendor_boot vendor_boot.img).
5. Boot to recovery.
6. Naviate to Adb sideload option and press sideload.
7. Now from pc type adb sideload rom.zip.
8. After sideloading is complete, format storage and reboot to system.

fastboot Images will be provided with march release.

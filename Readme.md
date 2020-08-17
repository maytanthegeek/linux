# Maytan Linux

This is not a new distro. This is MX Linux extension with a custom DE based on `bspwm` and stripped down of `xfce`. It includes lots of other useful applications. The DE and the applications are highly opinionated and try to enhance productivity with a focus on the keyboard.

## How to Run

### Pre-requisites

1. Your system must support UEFI as MBR support hasn't been added in this version.
2. You should have a USB drive handy.
3. [7zip ](https://www.7-zip.org/)

### Steps

1. Format your USB drive to FAT32.
2. Extract the contents of `linux.7z` onto the drive.
3. Reboot to BIOS.
4. Set boot priority of USB disk to the highest and turn off secure-boot.
5. Save settings and boot.
6. You should see the USB drive boot to an ugly grub menu.
7. Select `Run linux` from the menu and the OS should boot.

### Login Info

* Username: `maytan`
* Password: `maytan`
* Root password: `root`


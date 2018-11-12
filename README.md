# Example repository

Hello world!

This is a second change

# Basic git commands

mkdir (create a directory)

git clone URL directoryName

git add fileName

git status

git commit -m "message"

git push origin master

Username: username

Password: password

git diff fileName

git log

git checkout fileName

git checkout hash

# Restoring my usb to its original state using Windows

Win + R + "cmd" + enter

Diskpart

List Disk

Select Disk X

Clean

Create Partition Primary

Active

Format fs=Fat32 Quick

Exit

# How to dual boot my Windows laptop with Linux using a pendrive

1. Download a Linux ISO file.

2. Download a program to write the ISO into a pendrive (https://www.pendrivelinux.com/universal-usb-installer-easy-as-1-2-3/)

3. Run the .exe and burn the ISO.

4. Open Disk Management, select the disk in which you are going to free space (1GB == 1024MB)

  If you are using a Dell xps, open System configuration > boot > check Safe boot (minimal) and OS boot information.
  
  Then, reboot and enter to the BIOS, change SATA operation to AHCI.
  
  Finally, reboot to Windows and reset boot mode to normal.

5. Plug the pendrive into the laptop and restart it.

6. While booting, enter to the boot menu and look for the option boot from removable media (usb)

7. Install Linux

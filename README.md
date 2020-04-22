# Hackintosh-X1-Carbon-3rd-Gen-
Catalina hackintosh opencore build for Thinkpad X1 carbon(3rd gen)

My specs:
  -intel core I7 5600U
  -intel hd graphics 5500
  -8 gb 1600 mhz ddr3
  -Realtek ALC3232 Audio (Realtek ALC292)
  -LCD Display 1920x1080 14"
  -Intel AC7265 Wireless/Bluetooth Card(THIS IS NOT GOING TO WORK WITH MACOS)
  -SAMSUNG MZNLN256HCHP-000L7 256gb ssd
  
What does not work:
  -Wireless/bluethoot (you have to change with a osx compatible)
  -hdmi port
  
  
BIOS SETTINGS:
  -Disable Security Chip
  -Disable Anti Theft Module
  -Disable TPM
  -Disable Legacy boot,go for UEFI only
  
Create a usb installer:
  I want to link a very well made guide to create an installer:https://www.tonymacx86.com/threads/guide-booting-the-os-x-installer-on-laptops-with-clover.148093/
  
  When you create the EFI partition do not install with clover as the guide says,just mount EFI partition and paste my  
  unzipped EFI folder.

# What is WindowsToGo?
WindowsToGo is a USB that is able to boot a full Windows Installation, Typically created by Windows Application , Rufus, this drive can enable you to boot with your own user on any Windows Computer.
# Installation
## Test No. 1 (Failed)
Creating the drive can not be created using a typical installation media as it is regarded as an external drive even after formatting it to NTFS and GPT. This Was tested using a Windows 11 Installation Media and was not Successful

## Test No. 2 (Succeeded)
Rufus has a built in feature to create a WinToGo USB which takes around twenty minutes and also create a Local User with mo Password, This Works very well as Windows 11 requires a microsoft account during setup

## Test No. 3 (Succeeded)
A program named WinToUSB made by a company called Hasleo works fine for begginers but requires for you to setup the whole PC yourself and a Microsoft account, not to mention you can only use a Home license unless you pay £30, Whereas it does have its good as you can convert your drive to a HDD or enable BitLocker
# Booting
Booting into the OS for the first time takes a while as it installs Drivers. Do NOT turn your PC off during this progress. Rufus installation comes with no password but requires you to change it during first boot.

# MacOS Boot
Booting with the drive with Macintosh Computers are a bit more complex, it requires different drivers. THIS ONLY WORKS WITH INTEL MACS.
## Downloading the Drivers
The Drivers are able to download here, https://support.apple.com/kb/DL1837?viewlocale=en_US&locale=en_US
## Saving the Drivers
Place the Extracted Drivers in a USB which is formatted as ExFat.
## Installing the Drivers
Hold Option while starting up with the WinToUSB and select the USB, connect a wired Keyboard and Mouse and go to the USB and click on the setup.exe file and install the app and all the drivers, this also allows you to quickly move to MacOS.
# Issues
## Public or School Computers
If the Bootloader is locked then boot into the BIOS first and then boot back in the bootloader befor going to the local Windows Installation.

Existing Issue: Browsing the Internet not working
# <img width="300" alt="IMG_1374" src="https://github.com/sanstechnology/Project1...WinToGo/assets/143093663/318b80c5-824a-4498-8aad-ee6be0c49c36">
# sans. technologies 
## Credit to NotArxy, CHXMPION, TechMateNS, TechMateAK

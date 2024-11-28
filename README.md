# Dell-Optiplex-7060-EFI-
Prebuilt Opencore EFI for the Dell Optiplex 7060 **Tower**.

Specs:
**i7 8700 (Coffee Lake)
| Intel UHD Graphics 630 (1536 MB)**

**Intel 370 series chipset motherboard (Dell OEM)**

**Intel gigabit ethernet**

**WD Blue SN520 512GB NvMe SSD**

**Seagate 1TB SSHD FireCuda Gaming ST1000LX015 HDD**

**Realtek integrated audio ALC3236**

No wireless internet card.


# Whats working:
**Intel UHD Graphics 630** ✅

**Intel gigabit ethernet** ✅

**Realtek integrated audio ALC3236** ❌

**Realtek memory card Reader** ❔ (Not tested)

**Panasonic Matshita DVD RW** ❔ (Not tested)

**Real Time Clock (RTC)** ❔(Not tested)



# Note:-

Please update the SMBIOS information with your own serial number MLB, etc using GenSMBIOS, otherwise the EFI will not work. 
You can enable verbose boot by adding -v to the boot args incase your hackintosh is not booting.
If you do not use a NvMe SSD, please remove NvMefix.kext from kexts and make a snapshot in ProperTree.
You can inform me of any issues or bugs.
**This EFI has been tested only on Ventura, it will be tested on higher versions later.**
**If you know the layout ID for the audio, please inform me,** I will update the EFI. Current layout ID is **3** and audio stil wont work.
**I reccomend installing this build on a NvMe or Sata SSD as it is pretty slow on the harddrive.**
**Real time clock is not confirmed to be working. (Will test)**





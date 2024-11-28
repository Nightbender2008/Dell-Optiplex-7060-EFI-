# Dell-Optiplex-7060-EFI-
Prebuilt Opencore EFI for the Dell Optiplex 7060 **Tower**.

Specs:
**i7 8700 (Coffee Lake)
| Intel UHD Graphics 630 (1536 MB)**

**8GB DDR4 2666MHZ Dual Channel**

**Intel 370 series chipset motherboard (Dell OEM)**

**Intel gigabit ethernet**

**WD Blue SN520 512GB NvMe SSD**

**Seagate 1TB FireCuda ST1000L HDD**

**Realtek integrated audio ALC3236**

No wireless internet card.


# Whats working:
**Intel UHD Graphics 630** ✅

**Intel gigabit ethernet** ✅

**CPU Turbo Boost** ✅

**IGPU Accelerator (Metal-2 HEVC H.264 Video Decode/EnCode)** ✅

**AirDrop & Airplay** ✅

**Sleep and wake support** ✅

# Untested/Not Working:-
**Realtek integrated audio and microphone ALC3236** ❌

**Realtek memory card Reader** ❔ (Not tested)

**Panasonic Matshita DVD RW** ❔ (Not tested)

**Real Time Clock (RTC)** ❔(Not tested) 

# BIOS Settings 
System Configuration → SATA Mode: AHCI

Secure Boot → Secure Boot Enable: Disabled

Security → TPM → Disable TPM

System Configuration → Serial Port→ Disable Serial Port

Intel® Software Guard Extensions™ → Intel® SGX™ → Disable Intel® SGX™

Hyperthreading → Enabled

VT/D → Enabled



# Note:-

**Please update the SMBIOS information with your own serial number MLB, etc using GenSMBIOS, otherwise the EFI will not work.**
You can enable verbose boot by adding -v to the boot args incase your hackintosh is not booting.
If you do not use a NvMe SSD, please remove NvMefix.kext from kexts and make a snapshot in ProperTree.
You can inform me of any issues or bugs.
**This EFI has been tested only on Ventura, it will be tested on higher versions later.**
**If you know the layout ID for the audio, please inform me,** I will update the EFI. Current layout ID is **3** and audio stil wont work.
**I reccomend installing this build on a NvMe or Sata SSD as it is pretty slow on the harddrive.**
**Real time clock is not confirmed to be working. (Will test)**


# Screenshots:-

[Screenshot 2024-11-28 at 10 55 50 PM](https://github.com/user-attachments/assets/ecba341c-aa8c-4529-a7e8-52c9b64fbbbf)
[Screenshot 2024-11-28 at 10 56 34 PM](https://github.com/user-attachments/assets/6ceb19c5-44a2-47fc-ab58-796ccc9153ef)
[Screenshot 2024-11-28 at 10 56 18 PM](https://github.com/user-attachments/assets/c383607d-b458-47ff-b7e0-c2da2b46e753)





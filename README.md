
# Welcome to my EFI repository

Changelog:
CillyCil - Updating for OpenCore 1.0.0 and macOS Sonoma
Adding Opencore 0.8.7 version

# My config
- macOS Sonoma 14.4.**1**
- Motherboard  **MSI MS-1551** with latest Bios version E1551IMS.10F
- Core i5-10210u
- Intel UHD 620 Mobile graphics
- Intel Kaby Lake HDMI @ Intel Comet Point-LP PCH 
- Realtek ALC 233 (seen as ALC 235) layout 29
- Screen CMN N156HCE-EN1 [15.6" LCD]
- WDC WDS250G2B0B-00YS70 (250 Gb, mSATA, Windows)
- HFS256G39TND-N210A (256 Gb, mSATA, macOS Sonoma)
- 16 GB random memory (i forgor)
- Intel Comet Point-LP PCH - USB 3.1 xHCI Host Controller
- **Realtek USB 2.0 Card Reader (work with https://github.com/0xFireWolf/RealtekCardReader)**
- Intel(R) Wireless-AC 9560 works with https://github.com/OpenIntelWireless/itlwm/releases
- Intel bluetooth works. https://github.com/OpenIntelWireless/IntelBluetoothFirmware/releases
- **Thanks OpenIntelWireless team**
- Keyboard works (brightness & audio mute/vol -/+) with ssdt
- trackpad works (with gesture & trackpad pref)
# What doesn't works
- Mute key works except for LED status (always on or always off. Depends on the last state under windows)
- USB C to HDMI adapter doesn't work correctly (flickering) **I think it works but am not sure**
- DRM for AppleTV or Netflix on Safari
- Sometimes unplugging USB-C will cause a restart? Do not know why

# Tips

- Make sure you have disabled secure boot in bios.
- You had to disabled CFG Lock in bios.
- At startup press suppr key to enter in bios.
- **Go to Advanced menu & press the magic combo keys**
- Press ALT + RIGHT-CTRL + RIGHT-SHIFT together then press F2 for see hidden feature
- Note (press also fn keys for azerty users)
- go to advanced->power & Performance ->CPU - Power Management Control ->CPU lock Configuration ->CFG lock
- **IF YOU CANNOT GET YOUR CAMERA TO WORK PRESS THE CAMERA BUTTON ON YOUR KEYBOARD AND IT WILL TURN ON**

# Thanks

- Acidanthera for opencore & most kexts
- Daliansky for OC-little & XiaoXinPro-13-hackintosh repository
- lietxa for https://github.com/lietxia/XiaoXinAir14IML_2019_hackintosh repository
- mledour for MSI-FNKEY SSDT https://github.com/mledour/MSI-GF63-9RCX_OpenCore-Hackintosh
- zxystd for intelbluetooth, itlwmx & heliport https://github.com/OpenIntelWireless/itlwm
- dortania https://dortania.github.io
- Pierre Dandumont for ² key https://www.journaldulapin.com/2020/05/28/faire-un-²-avec-un-clavier-apple/
- pqrs-org for Karabiner https://karabiner-elements.pqrs.org
- FaneCH for https://github.com/FaneCH/Vostro-3490-hackintosh HDMI out works !!!
- 0xFireWolf for https://github.com/0xFireWolf/RealtekCardReader Sdcard reader works !!!
- 5T33Z0 for https://github.com/5T33Z0/OC-Little-Translated/tree/f4490b9f46b828182cc0c0886a7388e982344e6c Oclittle translated
- hla64 for original repo https://github.com/hla63/Msi-modern-15-Hackintosh

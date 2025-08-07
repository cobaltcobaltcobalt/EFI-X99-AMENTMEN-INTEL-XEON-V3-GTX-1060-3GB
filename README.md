# Amentmen x99 + Xeon E5-26xx + GTX 1060 3GB

**Latest working macOS**: 14.7
<br>
**Current OpenCore**: 0.8.6

![Screenshot](https://github.com/cobaltcobaltcobalt/EFI-X99-AMENTMEN-INTEL-XEON-V3-GTX-1060-3GB/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-06-22%20%D0%B2%2004.31.20.png?raw=true)

## Complete hardware specs
- Intel Xeon E5-2680 v3
- Amentmen x99 
- Nvidia GTX 1060 3GB
- Áudio Codec: Realtek ALC662
- Ethernet: Realtek® 8111F

## What works
* Graphics: Nvidia GTX 1060 via OCLP (There are some issues with transparency, but most of the time they look normal)
* Dual monitor setup DP + DVI @ 165HZ (although some animations are not that smooth due to lack of Metal 2 support)
* USB
* USB Audio
* Sleep
* Speakers
* Microphone
* Ethernet
* AirDrop
* Apple Services

## Unknown (Didn’t test)：

* Wi-Fi
* Bluetooth
* HDMI Audio
* Onboard audio
* Siri
* Overclocking

## Known issues：

* Anydesk crashes on connect from other device to hackintosh,  haven’t found fix yet. Connecting from hackintosh to other devices works correctly. 

## What doesn't work
- Correct USB Mapping :(

## Kexts used:
- AppleALC.kext 
- CpuTscSync.kext
- Lilu.kext
- RealtekRTL8111.kext
- RestrictEvents.kext
- SMCProcessor.kext 
- SMCSuperIO.kext
- UTBMAP.kext
- USBToolBox.kext
- VirtualSMC.kext 
- WhateverGreen.kext 
- XHCI-unsupported.kext 

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [BASE EFI Intel Haswell-E (HEDT)](https://github.com/luchina-gabriel/BASE-EFI-INTEL-HEDT-4THGEN-X99-HASWELL-E)

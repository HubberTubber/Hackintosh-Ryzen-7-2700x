# Hackintosh Ryzen OpenCore Build

First try at building a hackintosh for my Ryzen 2700X system, with a GeForce GTX 980-TI. Using High Sierra, but will work with the latest with a supported GPU. Ethernet works with **Realtek RTL8168H** (Included in build). If you want to use the intel chipset, then replace the realtek kext with the intel one and reflect that in the config.plist.


# Setup

- Follow [Dortania OpenCore Guide](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/winblows-install.html)
- Generate an SMBIOS with [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
- Copy EFI folder to USB
- Start up USB

# Verified Compatibility
Component                      |Compatibility                |
-------------------------------|-----------------------------|
CPU           |Ryzen 7 2700X            |
Motherboard            |ASUS X570 Prime-P          |
RAM |32GB Patriot Viper Gaming DDR4 3600MHZ|
GPU |GTX 980-TI |
Ethernet | Realtek RTL8111H |

**macOS version**: 13.6
**OpenCore version**: 0.5.6 (Update OpenCore to run later version of macOS)


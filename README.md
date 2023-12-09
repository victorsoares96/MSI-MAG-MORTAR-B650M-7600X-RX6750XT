# HACKINTOSH MSI-MAG-MORTAR-B650M-7600X-RX6750XT

![macOS](images/macos.png)

**OpenCore : 0.9.6**

**macOS ：13.6.1**

**SMBIOS : MacPro7,1**

### Specification

| **Component**    | **Model**                  |
| ---------------- | -------------------------- |
| CPU              | AMD Ryzen 5 7600X               |
| Motherboard      | MSI(MAG) B650M MORTAR WIFI (BIOS 7D76vA6) |
| RAM              | XPG 32GB(16GB×2) DDR5 6000Mhz |
| Audio Chipset    | ALC4080 Codec                  |
| GPU              | XFX RX 6750XT 12GB              |
| Ethernet         | RTL8125B 2.5Gbps LAN            |
| WiFi & Bluetooth | AMD RZ616 Wi-Fi 6E         |
| OS Disk(nvme)    | NVME XPG Gen4 1TB            |

### Bios Setup

  Based on Load Optimize defaults

- TMP (Disable)
- Secure Boot (Disable)
- Resize BAR (Disable)
- 4G Decoding (Disable)
- Change to CSM mode

More Info: [AMD BIOS Settings](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#amd-bios-settings)

### Works

- Audio
- RX 6750XT Video (NootRX)
- Ethernet
- USB  
  ***If you have USB problems, You can use it to generate your own usb configuration information***

### Not Works

- Wi-Fi
- Bluetooth

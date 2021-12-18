# Specifications  
    Gigabyte B460M Aorus Elite (Bios: F5)
     - Audio: Realtek® ALC1200 codec
     - Ethernet: Intel® Ethernet Connection I219V12
     Intel Core i5 10400
     Ram 2 x 16GB Kingston DDR4 2666 CL16
     SSD Micron Crucial MX500 500GB SATA 
     GPU Powercolor Radeon RX570 4GB (AXRX5704GBD5-3DHD/OC)
     Wifi + Bluetooth BCM94360CD 
     Monitor ASUS Tuf Gaming VG289Q 28-inch 4k
  ![image](https://github.com/ericai0803/Gigabyte-B460M-Aorus-Elite-Hackintosh-Open-Core/blob/main/Images/system%20info.jpg)
     
# OpenCore (Version: 0.7.7) + macOS Monterey (12.0.1)
* OC Install Guide https://dortania.github.io/OpenCore-Install-Guide/
* OC 0.7.7 Pkg https://github.com/dortania/build-repo/releases
* OC 0.7.7 Configuration https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Configuration.pdf
* 我和我黑蘋果 https://www.imacpc.net/archives/3340
# BIOS Settings
## Enable
* VT-x
* Above 4G decoding
* Hyper-Threading
* EHCI/XHCI Hand-off
* OS type: Windows 10 UEFI Mode
* DVMT Pre-Allocated(iGPU Memory): 64MB
* SATA Mode: AHCI
## Disable
* Fast Boot
* Secure Boot
* Serial/COM Port
* VT-d (can be enabled if you set DisableIoMapper to YES)
* CSM
* CFG Lock 
# Kexts include
* Lilu
* VirtualSMC
* WhateverGreen
* AppleALC
* IntelMausi
* NvMeFixup 
* XHCI-unsupported
* USBPorts
# Work
* AirDrop & Handoff
* Rear Jack Audio Output + Input and Front Jack
* Ethernet
* WIFI
* Bluetooth
* All USB Ports
* Restart, Sleep and Shutdown
# Known issue
* Etc
# Result
![image](https://github.com/ericai0803/Gigabyte-B460M-Aorus-Elite-Hackintosh-Open-Core/blob/main/Images/Intel%20Gadget.jpg)

![image](https://github.com/ericai0803/Gigabyte-B460M-Aorus-Elite-Hackintosh-Open-Core/blob/main/Images/videoproc.jpg)

![image](https://github.com/ericai0803/Gigabyte-B460M-Aorus-Elite-Hackintosh-Open-Core/blob/main/Images/Geek5%20CPU%20Bench.png)

![image](https://github.com/ericai0803/Gigabyte-B460M-Aorus-Elite-Hackintosh-Open-Core/blob/main/Images/Geek5%20GPU%20Bench.png)

![image](https://github.com/ericai0803/Gigabyte-B460M-Aorus-Elite-Hackintosh-Open-Core/blob/main/Images/%20CineBenchR20.png)

# Note for you
![image](https://github.com/ericai0803/Gigabyte-B460M-Aorus-Elite-Hackintosh-Open-Core/blob/main/Images/Sereial.png)
##### Please use your own SN, UUID and MLB number.

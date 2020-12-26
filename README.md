## OpenCore EFI for HP EliteBook 840G4 Hackintosh for Catalina and Big Sur

## ALL Working! Sleep/Wake, IntelWifi 8260 (native), SD-Card Reader
![Screenshot](https://github.com/DominikHackintosh/HP-EliteBook-840-G4-Hackintosh-Big-Sur/blob/master/Screen%20Shot%202020-12-26%20at%2004.19.00.png?raw=true)


##### Laptop Specifications:
- Intel Core i5 7300U Quad Core CPU
- Intel HD 620 Graphics
- 32GB DDR4 2133MHz RAM
- 14in Full HD LED Display
- SMBus Synaptics TouchPad
- Intel Wifi AC 8260
- 2 USB 3.0 Ports, 1 USB Type-C Port
- Display Port
- SD Card Reader
- 1000GB Crucial BX500 NVME M.2 SSD
- 256GB Samsung SSD (Sata)

##### BIOS Setup:
##### NOW all new BIOS Versions are working! ((((Update/Downgrade!!! to BIOS P78 v.1.29 / v.1.3.1 (extremely important becaus newer Versions don´t work!!!!))))

- Disable TPM Security
- Disable Physical Presence Interface
- Disable Intel SGX
- Enable System Management Command
- Disable Fast Boot
- Enable USB Storage Boot
- Disable Network PXE Boot
- Disable Power On when AC Detected
- Disable Power On when Lid is Opened
- Disable Secure Boot
- Disable Legacy Boot
- Enable Turbo Boost
- Enable Hyperthreading
- Enable Multi-Processor
- Enable VT-x
- Disable VT-d
- Disable Fast Charge
- Enable Turbo Boost on DC
- Disable HP Application Driver
- Enable LAN Controller
- Disable Wake on LAN
- Disable Lock Wireless Button
- Enable WLAN
- Enable Bluetooth
- Disable LAN/WLAN Auto Switching
- Enable Fan Always On while on AC Power
- Enable Fan Quietness Mode
- Enable Boost Converter
- Enable Integrated Camera
- Enable Media Card Reader
- Disable Smart Card
- Enable Runtime Power Management
- Disable Extended Idle Power States
- Disable Deep Sleep
- Enable Wake when Lid is Opened
- Disable Wake when AC is Detected
- Disable Wake on USB
- Enable Power Control

#### Known issues:

SD-Card Reader does initialize but does not mount SD-Card after sleep

#### Credit:

- Apple for MacOS
- vit9696 for OpenCore
- Dortania's Guide for OpenCore Install
- InsanelyMac's OpenCore forums for finding issues with hardware and their work arounds
- RehabMan for DSDT-Patches
- OpenIntelWireless/itlwm for insane Intel Wifi project ;)

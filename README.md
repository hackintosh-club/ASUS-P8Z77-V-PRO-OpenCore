# ASUS-P8Z77-V-PRO Hackintosh OpenCore EFI

### [简体中文](README.zh_CN.md)

### OpenCore

[OpenCore 0.8.0](https://github.com/acidanthera/OpenCorePkg)

### OS Version Tested

- macOS Catalina 10.15.x

### Hardware

- CPU: i7-3770k (3rd Gen) Ivy Bridge
- GPU: Intel HD Graphic 4000
- RAM: 32GB DDR3
- Motherboard: Asus P8Z77-V LX
- Audio: Realtek ALC892
- Ethernet Card: Intel 82579V
- Wifi Card: BCM94360CD

### Notes
 - ACPI - SSDT-PM.aml
 - if you have different cpu (like i5 3570k)，you need to see this and build your own SSDT-PM [Sandy and Ivy Bridge Power Management](https://dortania.github.io/OpenCore-Post-Install/universal/pm.html#sandy-and-ivy-bridge-power-management)  
 - Use [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) build your own SMBIOS
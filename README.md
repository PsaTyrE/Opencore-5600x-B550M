# Aourus B550M Desktop Ryzentosh (R5 5600x)
OpenCore bootloader config files for my workstation hackintosh.

GT 710 support arrived on Catalina

# System Information

| Name          | Model               |
| :------------ |:------------------: |
| CPU           | RYZEN 5 5600X       |
| GPU           | MSI GT 710          |
| SSD           | VGEN Hyper          |
| Board         | AOURUS B550M Pro -P |
| Ethernet      | LucyRTL8125Ethernet |
| MacOS         | Catalina            |

# Guide

https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html

# SMBIOS

Selected: MacPro7,1

Don't forget to change device uuid, board serials and network mac address Go to https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#platforminfo For information on setting up SMBIOS platform info

# KEXT Used

| KEXT                              |
| :-----------------------------:   |
| AMDRyzenCPUPowerManagement.kext   |
| AppleALC.kext                     |
| AppleMCEReporterDisabler.kext     |
| Lilu.kext                         |
| LucyRTL8125Ethernet.kext          |
| RestrictEvents.kext               |
| VirtualSMC.kext                   |
| WhateverGreen.kext                |


# Pre Install
1. Update SMBIOS and MAC address
2. Turn on 4G Above encoding, Turn off Resizable bar support

# Post Install
Upgrade OpenCore versions





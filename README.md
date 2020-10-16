# Gigabyte G1.Sniper M7 Hackintosh

Opencore Bootloader EFI and config.plist file with all required Drivers and Kexts for Gigabyte G1.Sniper M7. Should work with Both Skylake & Kaby Lake. (Only Tested With Skylake i5-6500).

## Included Software Versions

OpenCore - 0.6.2
AppleALC - 1.5.3
IntelMausi - 1.0.4
Lilu - 1.4.8
VirtualSMC -  1.1.7
WhateverGreen - 1.4.3

## BIOS SETTINGS

OS Mode: 
    Other OS with UEFI Only 
    or, Windows 8/10 (CSM Disabled)
Secure Boot: 
    Disabled
Aboce 4G Decode: 
    Enabled
SuperIO: 
    Disabled
VD-x: 
    Enabled
VT-d: 
    You can leave it disabled or enable it if you beed it for Other OS. (MacOS can't/doesn't use VT-d)

## What's Working

1. Boot Logo
2. Onboard Audio
3. Hardware Decoding using iGPU
4. Xcode and Android Studio
5. Netflix on 720p
6. Tested with macOS 10.15.7 (Latest Build)

## What's NOT Working 

1. Sleep Mode (Display can't power on ater sleep)
2. DRM (iGPU DRM broken since 10.12.2)

## What's Not Tested

1. iServices 

## My Hardware Config

* CPU: Intel Core i5-6500
* Motherboard: Gigabyte G1.Sniper M7 (B150 Chipset)
* RAM: 2x8GB G.Skill Ripjaws X
* SSD: Netac 256GB NVMe SSD

## Licenses & Attribution 

Most of the Included stuffs here are  BSD-3-Clause Licensed and developed by `acidanthera` developers and other open source community developers. Config files and EFI partition prepared by following `dortania - Hackintosh Guides` and some trial & errors. 

Enjoy. 
<h1 align="center"> macOS on Lenovo Thinkpad E570 </h1>

<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Lenovo%20ThinkPad%20E570.png" alt="Thinkpad E570" width="750">
</p>

<h4 align="center"> OpenCore config for Hackintosh Lenovo Thinkpad E570 </h4>

<p align="center">
<a href="https://www.apple.com/macos/sonoma-preview/">
  <img src="https://img.shields.io/badge/macOS-Sonoma-green" width="170"/> </a>
<a href="https://github.com/acidanthera/OpenCorePkg/releases">
  <img src="https://img.shields.io/badge/OpenCore-0.9.8-9cf" width="160"/> </a>
<a href="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/releases">
  <img src="https://img.shields.io/badge/release-EFI-blue.svg" width="120"/> </a>
  <a href="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/issues"> 
  <img src="https://img.shields.io/github/issues/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh" width="145"/> </a>
<a href="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#changelog">
  <img src="https://img.shields.io/badge/Changelog-orange.svg" width="108"/> </a>
</p>
<p align="center">
<a href="https://t.me/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-2CA5E0?logo=Telegram&logoColor=white" width="150"/> </a>
<a href="https://www.youtube.com/c/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-red?logo=YouTube&logoColor=white" width="150"/> </a>
<a href="https://www.paypal.com/paypalme/sevenpay">
  <img src="https://img.shields.io/badge/-@sevenpay-white?logo=PayPal" width="140"/> </a>
<a href="https://www.buymeacoffee.com/yusufklncc">
  <img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" width="150"/> </a>

## Table of Contents
  - [Screenshots](#screenshots-)
  - [Original Hardware](#original-hardware--)
  - [Modifications](#modifications--)
  - [macOS Update History](#macos-update-history)
  - [What's working](#whats-working--)
  - [Kexts Used](h#kext-used)
  - [SSDTs Used](#ssdt-used)
  - [Changelog](#changelog)
  - [Installation Steps](#installation-steps)
  - [How to make it better?](#how-to-make-it-better)
    - [Advanced Resolution](#advanced-resolution)
  - [Credits](#credits)
  - [Donate](#-donate---ba%C4%9F%C4%B1%C5%9F-)
  
## Screenshots 📷

### CPU Usage and Temperature  
#### - Normal

  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/CPU/Normal%20CPU%20Frequency%20and%20Temperature.png" width="300"><img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/CPU/Normal%20CPU%20Usage.png" width="390">
  
#### - Maximum

  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/CPU/Max%20CPU%20Frequency%20and%20Temperature.png" width="300"><img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/CPU/Max%20CPU%20Usage.png" width="390">

### Sonoma
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/macOS%20Desktop/Sonoma-14-3.png">
</p>

<details>
<summary>Sonoma</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/macOS%20Desktop/Sonoma.png">
</p>
</details>  
  
<details>
<summary>Ventura</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/macOS%20Desktop/Ventura.png">
</p>
</details>

<details>
<summary>Monterey</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/macOS%20Desktop/Monterey.png">
</p>
</details>

<details>
<summary>Big Sur</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/macOS%20Desktop/Big%20Sur.png">
</p>
</details>

<details>
<summary>Catalina</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/macOS%20Desktop/Catalina.png">
</p>
</details>

<details>
<summary>Mojave</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/macOS%20Desktop/Mojave.png">
</p>
</details>

<details>
<summary>High Sierra</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/macOS%20Desktop/High%20Sierra.png">
</p>
</details>

<details>
<summary>Sierra</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/macOS%20Desktop/Sierra.png">
</p>
</details>

## Original Hardware  💻
Type | Spec | Status
:---------|:---------|:----------
Model Name      | Lenovo Thinkpad E570 (20H500C5TX) | ✅
CPU              | Intel(R) Core(TM) i5-7200U CPU @ 2.50GHz Kaby Lake | ✅
RAM           | SK Hynix HMA851S6AFR6N-UH 8(4+4) GB 2133 MHz DDR4 | ✅
Internal Graphics Card | Intel(R) HD Graphics 620 (1 GB) | ✅
Wi-Fi             | Qualcomm Atheros QCA9377 | ❌
Ethernet          | Realtek RTL8111/8168/8411 | ✅
Audio       | Conexant CX20753/4 | ✅
Touchpad | SynPS/2 Synaptics TouchPad | ✅
SD Card Reader | O2 Micro SD/MMC | ✅
Fingerprint | Validity Sensor VFS5011 | ❌
Display | BOE CQ LCD Monitor(15.5 inch) | ✅
Camera | Acer Integrated Camera | ✅
  
## Modifications  🔨
Type | Spec | Status
:---------|:---------|:----------
Wi-Fi | Dell Wireless 1820A ac (BCM4350 + BCM2045A0) | ✅
USB Wi-Fi | TL-WN823N | ✅ 

- DW1820A not working on macOS Sonoma Beta 1. We have to use Intel Wi-Fi or USB Wi-Fi.
- You have to install USB drivers for working USB adapter.

## macOS Update History
- ✅ macOS Sonoma 14.0 (Currently testing)
- ✅ macOS Ventura 13.4 (Currently using)
- ✅ macOS Monterey 12.6
- ✅ macOS Big Sur 11.7.3
- ✅ macOS Catalina 10.15.7
- ✅ macOS Mojave 10.14.6
- ✅ macOS High Sierra 10.13.6
- ✅ macOS Sierra 10.12.6

## What's working  💻
Type | Status
:---------|:---------
Turbo boost and CPU frequency stage |  ✅
Intel HD Graphics 620              |  ✅
Brightness control                  |  ✅
HDMI                                |  ✅
Audio Conexant CX20753/4            |  ✅
Realtek Ethernet RTL8111            |  ✅
DW1820A Wi-Fi and Bluetooth, Airdrop, Handoff, SideCar, iMessage..         |  ✅
USB 3.0 and Type-C (with Port Map)        |  ✅
Touchpad (14 gestures are working)   |  ✅
Battery status   |  ✅
Camera   |  ✅
Micro SD Card Reader | ✅
S3 Sleep / Wake   |  ✅
S4 Hibernation / Wake   |  ✅
Shutdown / Reboot   |  ✅
Fn shortcut keys   |  ✅
  
## Kext Used
Kext | Info | MinKernel | MaxKernel
:---------|:---------|:---------|:---------
[Lilu](https://github.com/acidanthera/Lilu) | An open source kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS. | 8.0.0 |  
[VirtualSMC](https://github.com/acidanthera/VirtualSMC) | Advanced Apple SMC emulator in the kernel. Requires Lilu for full functioning. | 8.0.0 |  
[SMCBatteryManager](https://github.com/acidanthera/VirtualSMC) | a member of VirtualSMC that parses battery info. | 8.0.0 |  
[SMCProcessor](https://github.com/acidanthera/VirtualSMC) | a member of VirtualSMC that provides power info of processor temperature. | 11.0.0 |  
[WhateverGreen](https://github.com/acidanthera/WhateverGreen) | Various patches necessary for certain ATI/AMD/Intel/Nvidia GPUs. This is needed for Intel HD 620. | 10.0.0 |  
[AppleALC.kext](https://github.com/acidanthera/AppleALC) | An open source kernel extension enabling native macOS HD audio for not officially supported codecs without any filesystem modifications. | 8.0.0 |  
[NVMeFix](https://github.com/acidanthera/NVMeFix) | NVMeFix is a set of patches for the Apple NVMe storage driver, IONVMeFamily. | 18.0.0 |  22.9.9
[CPUFriend](https://github.com/acidanthera/CPUFriend) | A Lilu plug-in for dynamic power management data injection. | 10.0.0 |  
[CPUFriendDataProvider](https://github.com/acidanthera/CPUFriend) | A CPUFriend plug-in for CPU power management. | 10.0.0 |  
[FeatureUnlock](https://github.com/acidanthera/FeatureUnlock) | Lilu Kernel extension for enabling: Sidecar, NightShift, AirPlay to Mac, Universal Control. | 16.5.0 |  
[HibernationFixup](https://github.com/acidanthera/HibernationFixup) | An open source kernel extension providing a sync between RTC variables and NVRAM. | 16.0.0 |  
[RestrictEvents](https://github.com/acidanthera/RestrictEvents) | Lilu Kernel extension for blocking unwanted processes causing compatibility issues on different hardware and unlocking the support for certain features restricted to other hardware. | 16.0.0 |  
[NoTouchID](https://github.com/al3xtjames/NoTouchID) | Lilu plugin for disabling Touch ID support. | 16.0.0 |  19.5.9
[VoodooPS2Controller](https://github.com/acidanthera/VoodooPS2) | Contains updated Voodoo PS/2 Controller, improved Keyboard & Synaptics TouchPad. | 15.0.0 |  
[BrightnessKeys](https://github.com/acidanthera/BrightnessKeys) | Automatic handling of brightness keys based on ACPI Specification. | 16.0.0 |  
[AirportBrcmFixup](https://github.com/acidanthera/AirportBrcmFixup) | An open source kernel extension providing a set of patches required for non-native Airport Broadcom Wi-Fi cards. |  |  
[AirPortBrcm4360_Injector]() | An open source kernel extension providing a set of patches required for non-native Airport Broadcom Wi-Fi cards. |  | 16.9.9
[AirPortBrcmNIC_Injector]() | An open source kernel extension providing a set of patches required for non-native Airport Broadcom Wi-Fi cards. |  | 21.9.9
[BlueToolFixup](https://github.com/acidanthera/BrcmPatchRAM) | Injecting bluetooth firmware. | 21.0.0 |  
[BrcmBluetoothInjector](https://github.com/acidanthera/BrcmPatchRAM) | Injecting bluetooth firmware. | 14.0.0 | 20.9.9
[BrcmFirmwareData](https://github.com/acidanthera/BrcmPatchRAM) | BrcmPatchRAM kext is a macOS driver which applies PatchRAM updates for Broadcom RAMUSB based devices. | 14.0.0 |  
[BrcmPatchRAM2](https://github.com/acidanthera/BrcmPatchRAM) | BrcmPatchRAM kext is a macOS driver which applies PatchRAM updates for Broadcom RAMUSB based devices. | 15.0.0 | 18.9.9
[BrcmPatchRAM3](https://github.com/acidanthera/BrcmPatchRAM) | BrcmPatchRAM kext is a macOS driver which applies PatchRAM updates for Broadcom RAMUSB based devices. | 19.0.0 |  
[RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X) | OS X open source driver for the Realtek RTL8111/8168 family. |  |  
[RtWlanU](https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter) | USB Wi-Fi adapter. |  |  
[RtWlanU1827](https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter) | USB Wi-Fi adapter. |  |  
[HoRNDIS9.2](https://github.com/jwise/HoRNDIS) | Android USB Tethering. |  |  
[USBPorts]([https://www.youtube.com/watch?v=rlTDHkPzjAk&t=654s](https://github.com/benbaker76/Hackintool)) | Kext to inject mapped USB ports |  |  
  
## SSDT Used
SSDT | Info | Status
:---------|:---------|:---------
[SSDT-PTSWAK](https://github.com/5T33Z0/OC-Little-Translated/tree/main/04_Fixing_Sleep_and_Wake_Issues/PTSWAK_Sleep_and_Wake_Fix) | Comprehensive Sleep and Wake Patch. | Functional
[SSDR-EXT5-TP-LED](https://github.com/5T33Z0/OC-Little-Translated/tree/main/04_Fixing_Sleep_and_Wake_Issues/PTSWAK_Sleep_and_Wake_Fix) | Fixes ThinkPads breathing light of the Power Button LED will not return to normal after waking up. Also fixes an issue where the F4 microphone indicator status is not normal after waking up on older ThinkPad models. | Functional
[SSDT-AC](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/AC_Adapter_(SSDT-AC)) | Attaches an AC Adapter Device existing in a Laptop's DSDT to the AppleACPIACAdapter service in the IORegistry of macOS. | Cosmetic
[SSDT-BATT](https://dortania.github.io/OpenCore-Post-Install/laptop-specific/battery.html#battery-status) | Fixes the battery status indicator. | Functional
[SSDT-DMAC](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/DMA_Controller_(SSDT-DMAC)) | Adds Direct Memory Access Controller (DMAC) device to IORegistry. | Cosmetic
[SSDT-EC-USBX](https://dortania.github.io/Getting-Started-With-ACPI/Universal/ec-fix.html#fixing-embedded-controller-ssdt-ecusbx) | Adds a fake Embedded Controller (SSDT-EC) and enables USB Power Management (SSDT-EC-USBX). | Functional
[SSDT-FIXSHUTDOWN](https://dortania.github.io/OpenCore-Post-Install/usb/misc/shutdown.html#fixing-shutdown-restart) | Fixes Shutdown/Restart. Due to a missing S5 call that powers down the controller. | Functional
[SSDT-FWHD](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Fake_Firmware_Hub_(SSDT-FWHD)) | Adds Fake Firmware Hub Device (FWHD) device to the IORegistry in macOS. | Cosmetic
[SSDT-HPET](https://dortania.github.io/Getting-Started-With-ACPI/Universal/irq.html#fixing-irq-conflicts-ssdt-hpet-oc-patches-plist) | Fixes IRQ conflicts. Required for on-board sound to work. | Functional
[SSDT-OC-XOSI](https://dortania.github.io/Getting-Started-With-ACPI/ssdt-methods/ssdt-prebuilt.html#trackpad) | OS Check Fix patch to simulate a version of Windows for Darwin. | Functional
[SSDT-PLUG](https://dortania.github.io/Getting-Started-With-ACPI/Universal/plug.html#fixing-power-management-ssdt-plug) | Allow the kernel's XCPM(XNU's CPU Power Management) to manage CPU's power management. | Functional
[SSDT-PMC](https://github.com/corpnewt/SSDTTime) | It specifically brings back NVRAM support and requires very little configuration for the end user. | Functional
[SSDT-PNLF](https://dortania.github.io/Getting-Started-With-ACPI/Laptops/backlight.html) | Adds Backlight Control for Laptop Screens. | Functional
[SSDT-PWRB-SLPB_STA0B](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Power_and_Sleep_Button_(SSDT-PWRB:SSDT-SLPB)) | Enabling Power and Sleep Buttons. | Functional
[SSDT-RTC_STA0F](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/System_Clock_(SSDT-RTC0)) | Force-enable the RTC Device. | Functional
[SSDT-SBUS-MCHC](https://dortania.github.io/Getting-Started-With-ACPI/Universal/smbus.html) | Fixes System Management Bus and Memory Controller in macOS. | Functional

## boot-args Used
boot-arg | Info
:---------|:---------
-v | Enables verbose.
-no_compat_check | macOS Sonoma not support MBP14,1. So we have to use this argument for boot Sonoma.
brcmfx-country=#a | Changes the country code to XX (US, CN, #a, ..)
darkwake=0 | Disables darkwake.
swd_panic=1 | Avoids issue where going to sleep results in a reboot
-noDC9 | Fixes sleep issues.
-lilubetaall | Required for macOS Sonoma right now.

## Changelog

<details>
<summary>2023-06-07</summary>

- <b>Added</b>
  - Kernel
    - Add
      - USBPorts: For macOS Sonoma.
      - RtWlanU: USB Wi-Fi Adapter for macOS Sonoma.
      - RtWlanU1827: USB Wi-Fi Adapter for macOS Sonoma.
  - NVRAM
    - 7C436110-AB2A-4BBB-A880-FE41995C9F82
      - bluetoothExternalDongleFailed
        - 00 : Bluetooth Support for macOS 13.4 and later.
      - bluetoothInternalControllerInfo
        - 0000000000000000000000000000 : Bluetooth Support for macOS 13.4 and later.
      - boot-args
        - -lilubetaall for macOS Sonoma.
        - -no_compat_check for macOS Sonoma.
- <b>Changed</b>
  - Kernel
    - Add
      - NVMEFix: Max Kernel 22.9.9. Because macOS Sonoma not supported.
  - NVRAM
    - 7C436110-AB2A-4BBB-A880-FE41995C9F82
      - csr-active-config
        - 03080000 for USB Wi-Fi Adapter.
  - PlatformInfo
    - SMBIOS to MBP15,1 for macOS Sonoma installation. Change to 14,1 after installation.
- <b>Removed</b>
  - ACPI
    - Add
      - SSDT-KBD.aml: Useless
  - Kernel
    - Add
      - USBToolBox
      - UTBMap
  
</details>  

<details>
<summary>2023-04-25</summary>

- <b>Added</b>
  - Kernel
    - Add
      - USBToolBox: Inject Mapped USB ports.
      - UTBMap: USB port map.
- <b>Removed</b>
  - Kernel
    - Add
      - USBMap
      - USBMapLegacy
  
</details>  
  
<details>
<summary>2022-04-25 21:43</summary>

- <b>Added</b>
  - DeviceProperties
    - Ethernet
      - ´built-in 01 DATA´ for en0.
  - Kernel
    - Add
      - Min and Max Kernel Values
      - USBMap: Mapped USB ports for Catalina and newer.
      - USBMapLegacy: Mapped USB ports for Mojave and older.
      - BrcmBluetoothInjector: Bluetooth injection for Big Sur and older.
      - BrcmPatchRAM2: Bluetooth injection from Sierra to Mojave.
- <b>Changed</b>
    - Kernel
      - Quirks
        - CustomSMBIOSGuide: False
    - Misc
      - Boot
        - LauncherOption: Full
    - PlatformInfo
      - UpdateSMBIOSMode: Create
    - UEFI
      - Input
        - PointerSupport: False
- <b>Removed</b>
  - Kernel
    - Add
      - VoodooPS2Mouse
  
</details>
  
<details>
<summary>2022-03-25 16:25</summary>

- <b>Added</b>
  - Kexts
    - SMCBatteryManager: For true graphic in System Preferences.
    - RestrictEvents: For changed CPU name on About This Mac. (Intel(R) Core(TM) i5-7200U CPU @ 2.50GHz)
    - USBToolBox: Injects UTBMap.kext.
    - UTBMap: Mapped USB Ports.
- <b>Changed</b>  
    - config
      - Edited for CPU name. Don't change CPUType value.
        - Intel(R) Core(TM) i5-7200U CPU @ 2.50GHz. 
- <b>Removed</b>
  - Kexts
    - ACPIBatteryManager: Battery graphic issue on System Preferences.
    - SMCSuperIO: Laptop doesn't have a fan sensor.
    - USBInjectAll: No need anymore.
    - USBPorts: USBToolBox and UTBMap is using now.
  
</details>
  
<details>
<summary>2022-03-23 18:35</summary>

- <b>Added</b>
  - Kexts
    - BrightnessKeys: Brightness control on keyboard.
      - ACPI Patch
        - Rename (NBCF, 0x00) to Name (NBCF, 0x01)
- <b>Disabled</b>
  - ACPI
    - SSDT-CLICKPAD some compabilty problems.
    - SSDT-KBD
      - Using BrightnessKeys.kext and ACPI patch.
      - Disabled Rename _Q14 to XQ14 (TP-up)
      - Disabled Rename _Q15 to XQ15 (TP-down)
</details>

<details>
<summary>2022-03-23 15:15</summary>

- <b>Added</b>
  - ACPI
    - SSDT-AC for AC adapter in IORegistryExplorer.
    - SSDT-CLICKPAD for better touchpad.
    - SSDT-DMAC for DMAC device in IORegistryExplorer.
    - SSDT-EXT5-TP-LED for fix led on power button.
    - SSDT-FWHD for FWHD device in IORegistryExplorer.
    - SSDT-KBD for brightness control from keys.
      - ACPI Patch
        - Rename PNLF to XNLF
        - Rename _Q14 to XQ14 (TP-up)
        - Rename _Q15 to XQ15 (TP-down)
    - SSDT-PMC 
    - SSDT-PTSWAK for better sleep and wake.
      - ACPI Patch
        - Name0D-03 to 00
        - Name0D-04 to 00
        - Name6D-03 to 00
        - Name6D-04 to 00
        - Rename _PTS to ZPTS(1,N)
        - Rename _WAK to ZWAK(1,N)
    - SSDT-PWRB-SLPB_STA0B for power and sleep button.
    - SSDT-RTC_STA0F for enable RTC device.
  - Kexts
    - ACPIBatteryManager: For AppleSmartBatteryManager on IORegistryExplorer.
- <b>Changed</b>
  - ACPI
    - SSDT-XOSI to SSDT-OC-XOSI
      - ACPI Patch
        - Rename _OSI to XOSI (OS)
  - Kexts
    - FeatureUnlock 1.0.7 to 1.0.6 for fix Airplay to Mac.
- <b>Removed</b>
  - Kexts
    - SMCBatteryManager: Because using ACPIBatteryManager.kext
    - SMCLightSensor: Because laptop doesn't have a sensor.
  
</details> 

## Installation Steps

### Downloading OSX Image
- Click to OneDrive link and download it.
  - [Ventura](https://github.com/yusufklncc/Hackintosh-for-All-Computers#-macos-ventura-)
  - [Monterey](https://github.com/yusufklncc/Hackintosh-for-All-Computers#macos-monterey)
  - [Big Sur](https://github.com/yusufklncc/Hackintosh-for-All-Computers#macos-big-sur)
  - [Catalina](https://github.com/yusufklncc/Hackintosh-for-All-Computers#macos-catalina)
  
### Writing OSX Image
- Unzip the zip file to desktop.
- Download [balenaEtcher](https://www.balena.io/etcher/).
- Open program and click to `Flash from file`.
- Select the OSX image `.raw` file from the popup window.
- Click to `Select target` and select OSX image.
- Click to `Flash!` and allow app in popup window.
<p align="center">
  <img src="https://user-images.githubusercontent.com/78423442/154849816-0a04602a-9064-4780-9d4e-ed86254b4fea.png">

- When writing is finished, `remove` the USB stick and plug it back in.

### Setting EFI Folder
- When you plug USB back, you can see EFI partition in "My Computer"
- Open EFI partition.
- Delete default files.
- Copy downloaded EFI folder to EFI partititon.
- Open EFI/OC and set your config file. 
  - If you have Qualcomm Wi-Fi card. Delete default config and rename other one.
- Now you can boot from USB.

### Setting BIOS Settings 
  - Before you start, reset your BIOS settings to default.
  - `Disable`
    - Secure Boot
  - `Enable`
    - CSM
    
### macOS Installation
- Now let's turn off our computer and boot from USB. Choose the `Install macOS Monterey` (whatever you have) option on OpenCore menu and go to the installation screen.
- <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Installation/macOS%201.png">
- What to do on the following screens:
  - Select language and continue.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Installation/macOS%202.png">
  - Open `Disk Utility` from the menu to prepare our disk.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Installation/macOS%203.png">
  - Select `Show All Devices` from the `View` option and select the name of our disk and click `Erase`.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Installation/macOS%204.png">
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Installation/macOS%205.png">
  - Rename the disk and erase as `APFS/GUID`.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Installation/macOS%206.png">
  - Now close `Disk Utility` and select `Install macOS Sonoma` then next next next.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Installation/macOS%208.png">
  - Select renamed disk and click continue.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Installation/macOS%2010.png">
  - When the installation is finished,  `macOS Installer` option will be selected automatically every boot step until this option is `gone`.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Installation/macOS%2011.png">
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Installation/macOS%2012.png">
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Installation/macOS%2013.png">
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Installation/macOS%2014.png">
  - After last boot, the language selection screen will welcome us. Select language and continue.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Installation/macOS%2015.png">
  - Don't login `iCloud` account and continue. Because we need to set our `serial numbers and ROM for iCloud and iMessage`.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Installation/macOS%2016.png">
  - Now we can see `Desktop`.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Installation/macOS%2017.png">

### Post Installation

<br>

<details>
<summary><b>Broadcom Wi-Fi - Sonoma</b></summary>
  
- Dowload and Open [OCLP](https://github.com/dortania/OpenCore-Legacy-Patcher/releases). Click `Post-Install Root Patch` button.
<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Broadcom%20Wi-Fi%20Activation%20-%20OCLP/oclp-menu.png">
- Click `Start Root Patching`.
<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Broadcom%20Wi-Fi%20Activation%20-%20OCLP/post-install-menu.png">
- Click `Yes` and type password.
<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Broadcom%20Wi-Fi%20Activation%20-%20OCLP/start-root-patch.png">
<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Broadcom%20Wi-Fi%20Activation%20-%20OCLP/root-patching.png">
<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Broadcom%20Wi-Fi%20Activation%20-%20OCLP/root-patching-2.png">
- Click `Reboot`
<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Broadcom%20Wi-Fi%20Activation%20-%20OCLP/reboot-apply.png">
- Wi-Fi started working.
<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/Broadcom%20Wi-Fi%20Activation%20-%20OCLP/sonoma-wifi.png">
  
</details>  

- Open config file with `Text Edit`.
  - Search `HideAuxiliary` and change `false` value to `true`.
  - Search `SecureBootModel` and change `Disabled` value to `Default`.
    - If you have patched your system with `OCLP`, do not do this step.
  - Search `boot-args` and delete `-v` argument.
- Now we have to set our serial numbers and ROM value.
  - Download [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS/archive/refs/heads/master.zip) and open .command file. If program asks `Download Python` download it. After that select option 3.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/GenSMBIOS/GenSMBIOS%201.png">
  - Now list 5 SMBIOS first. `MacBookPro14,1`
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/GenSMBIOS/GenSMBIOS%202.png">
  - Select and copy first Serial.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/GenSMBIOS/GenSMBIOS%203.png">
  - Go [check](https://checkcoverage.apple.com/) serial number. Your serial should be like this. If not, try second serial.
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/GenSMBIOS/Check%20Serial.png">
  - Search MacBookPro15,1 and replace `Type > SystemProductName, Serial > SystemSerialNumber, Board Serial > MLB and SmUUID > SystemUUID` values. Now we will set our ROM value.
  - Go `System Setting > Netwotk > Ethernet > Details > Hardware`. If our MAC adress is `54:1A:AF:43:70:CA` remove `:` characters = `541AAF4370CA`. Convert it to [Base64](https://base64.guru/converter/encode/hex). 
  - Now we have `VBqvQ3DK`. Replace this with ROM value and save config file.
  - Delete default `USBPorts` kext in OC/Kexts and rename other one to `USBPorts`.
  - Restart computer and press `Space` key on OpenCore menu. Then enter `ResetNVRAM`. After that BIOS settings may change. Check it and boot macOS.
  - Now you can login iCloud, iMessage or other apple services and you can use macOS.

## How to make it better?
<details>  
  <summary> <h3>Advanced Resolution</h3> </summary>

- Use RDM for 1600x900 resolution which i am using currently. 
  - [Download RDM](https://onedrive.live.com/download?cid=83E8AF2D3EA2BA57&resid=83E8AF2D3EA2BA57%214113&authkey=ALMpGB-on3pqMmY)
  
- 1366x768
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/RDM/1366x768.png" alt="1366x768" width="600"> 
- 1600x900 
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/RDM/1600x900.png" alt="1600x900" width="600">
 
## How to Use?
- Download and open RDM.app. Follow images below.
<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/RDM/RDM%201680x1050.png" alt="1680x1050" width="600"> 

- Set resolution 1680x1050.
<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/RDM/RDM%20Edit%20Button.png" alt="RDM Edit Button" width="600"> 

<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/RDM/RDM%20Resolution%20Settings.png" alt="RDM Resolution Settings" width="600"> 

- Set what resolution you want. Click save, enter password and reboot.
<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Resources/RDM/RDM%201600x900.png" alt="1600x900" width="600">  

- Open RMD and select resolution what you want. This is only once.
</details>  
      
## Credits
  
 - [Dortania](https://dortania.github.io) for developing OpenCore.
 - [Apple](https://www.apple.com) for macOS.
 - [Acidanthera](https://github.com/acidanthera) for most of the kexts.
 - [RehabMan](https://github.com/RehabMan) for battery patches.
 - [Sniki](https://github.com/Sniki) for USB kext.
 - And anyone else that helped to develop and improve hackintoshing.

<h1 align="center"> Donate - Bağış </h1>
<p align="center">
<a href="https://github.com/yusufklncc/yusfklncc/blob/main/Donate%20-%20Ba%C4%9F%C4%B1%C5%9F.md">
  <img src="https://github.com/yusufklncc/yusfklncc/blob/main/Resources/Donate.png" width="300">

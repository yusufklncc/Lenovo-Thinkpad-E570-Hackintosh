<h1 align="center"> macOS on Lenovo Thinkpad E570 </h1>

<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/ThinkPad%20E570.png" alt="Thinkpad E570">
</p>

<h4 align="center"> OpenCore config for Hackintosh Lenovo Thinkpad E570 </h4>

<p align="center">
<a href="https://www.apple.com/macos/monterey/">
  <img src="https://img.shields.io/badge/macOS-Ventura_v13.0-orange" width="215"/> </a>
<a href="https://github.com/acidanthera/OpenCorePkg/releases">
  <img src="https://img.shields.io/badge/OpenCore-0.8.5-9cf" width="155"/> </a>
<a href="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/releases">
  <img src="https://img.shields.io/badge/release-EFI-blue.svg" width="115"/> </a>
  <a href="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/issues"> 
  <img src="https://img.shields.io/github/issues/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh" width="145"/> </a>
<a href="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#changelog">
  <img src="https://img.shields.io/badge/Changelog-green.svg" width="110"/> </a>
</p>
<p align="center">
<a href="https://t.me/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-2CA5E0?logo=Telegram&logoColor=blue" width="150"/> </a>
<a href="https://www.youtube.com/c/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-red?logo=YouTube&logoColor=white" width="150"/> </a>
<a href="https://www.paypal.com/paypalme/sevenpay">
  <img src="https://img.shields.io/badge/-@sevenpay-2CA5E0?logo=PayPal&logoColor=red" width="140"/> </a>

## Contents
  - [Screenshots](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#screenshots-)
  - [Original Hardware](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#original-hardware--)
  - [Modifications](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#modifications--)
  - [macOS Update History](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#macos-update-history)
  - [What's working](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#whats-working--)
  - [What's you have to do](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#whats-you-have-to-do--)
  - [Kexts Used](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#kext-used)
  - [SSDTs Used](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#ssdt-used)
  - [Changelog](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#changelog)
  - [How to make it better?](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#how-to-make-it-better)
    - [Advanced Resolution](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#advanced-resolution)
    - [Thinkpad's Click and Trackpad](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#thinkpads-click-and-trackpad)
    - [DW1820A Windows Driver](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#dw1820a-windows-1011-driver)
  - [Credits](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#credits)
  - [Donate](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#-donate---ba%C4%9F%C4%B1%C5%9F-)
  
## Screenshots 📷

### CPU Usage and Temperature  
- Normal

  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Normal%20CPU%20Frequency%20and%20Temperature.png" width="300">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Normal%20CPU%20Usage.png" width="400">
  
- Maximum

  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Max%20CPU%20Frequency%20and%20Temperature.png" width="300">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/Max%20CPU%20Usage.png" width="400">

<details>
<summary>Monterey</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/macOS%20Monterey.png">
</p>
</details>

<details>
<summary>Big Sur</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Big%20Sur.png">
</p>
</details>

<details>
<summary>Catalina</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Catalina.png">
</p>
</details>

<details>
<summary>Mojave</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Mojave.png">
</p>
</details>

<details>
<summary>High Sierra</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/High%20Sierra.png">
</p>
</details>

<details>
<summary>Sierra</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Sierra.png">
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
SD Card Reader | O2 Micro SD/MMC | ⚠️
Fingerprint | Validity Sensor VFS5011 | ❌
Display | BOE CQ LCD Monitor(15.5 inch) | ✅
Camera | Acer Integrated Camera | ✅
  
  
## Modifications  🔨

Type | Spec | Status
:---------|:---------|:----------
| Wi-Fi | Dell Wireless 1820A ac (BCM4350 + BCM2045A0) | ✅
  

## macOS Update History

- ✅ macOS Ventura 13.0 Beta 4 (Currently using)
- ✅ macOS Ventura 13.0 Beta 3
- ✅ macOS Monterey 12.6
- ✅ macOS Monterey 12.4 Beta 2  
- ✅ macOS Monterey 12.4 Beta 1
- ✅ macOS Monterey 12.3.1  
- ✅ macOS Monterey 12.3
- ✅ macOS Monterey 12.2.1  
- ✅ macOS Monterey 12.0.1
- ✅ macOS Big Sur 11.6.5
- ✅ macOS Big Sur 11.6.1
- ✅ macOS Big Sur 11.0.1
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
S3 Sleep / Wake   |  ✅  
S4 Hibernation / Wake   |  ✅  
Shutdown / Reboot   |  ✅  
Fn shortcut keys   |  ✅  
 
## What's you have to do  💻
  
Type | Info | Status
:---------|:---------|:----------
Micro SD Card Reader | Not working in OpenCore. You have to patch DSDT or use CLOVER | ⚠️ 
SMBIOS Settings  | With [GenSMBIOS] you should definitely set your SMBIOS settings and ROM value for iCloud and Apple services. ROM value is your ethernet MAC address. Be sure your ethernet is en0 in Hackintool. |  ⚠️
Rename config    |  If you have QCA rename no Wi-Fİ config. "config.plist". | ⚠️
  
## Kext Used 
 
Kext | Info 
:---------|:---------
[Lilu](https://github.com/acidanthera/Lilu) | An open source kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS.
[VirtualSMC](https://github.com/acidanthera/VirtualSMC) | Advanced Apple SMC emulator in the kernel. Requires Lilu for full functioning.
[WhateverGreen](https://github.com/acidanthera/WhateverGreen) | Various patches necessary for certain ATI/AMD/Intel/Nvidia GPUs. This is needed for Intel HD 620.
[SMCBatteryManager](https://github.com/acidanthera/VirtualSMC) | a member of VirtualSMC that parses battery info.
[SMCProcessor](https://github.com/acidanthera/VirtualSMC) | a member of VirtualSMC that provides power info of processor temperature.
[AppleALC.kext](https://github.com/acidanthera/AppleALC) | An open source kernel extension enabling native macOS HD audio for not officially supported codecs without any filesystem modifications.
[USBMap](https://www.youtube.com/watch?v=rlTDHkPzjAk&t=654s) | Kext to inject mapped USB Ports for Catalina and newer.
[USBMapLegacy](https://www.youtube.com/watch?v=rlTDHkPzjAk&t=654s) | Kext to inject mapped USB Ports for Mojave and older.
[VoodooPS2Controller](https://github.com/acidanthera/VoodooPS2) | Contains updated Voodoo PS/2 Controller, improved Keyboard & Synaptics TouchPad.
[RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X) | OS X open source driver for the Realtek RTL8111/8168 family.
[AirportBrcmFixup](https://github.com/acidanthera/AirportBrcmFixup) | An open source kernel extension providing a set of patches required for non-native Airport Broadcom Wi-Fi cards.
[BrcmPatchRAM](https://github.com/acidanthera/BrcmPatchRAM) | BrcmPatchRAM kext is a macOS driver which applies PatchRAM updates for Broadcom RAMUSB based devices.
[BlueToolFixup](https://github.com/acidanthera/BrcmPatchRAM) | Injecting bluetooth firmware on Monterey+.
[NVMeFix](https://github.com/acidanthera/NVMeFix) | NVMeFix is a set of patches for the Apple NVMe storage driver, IONVMeFamily.
[BrightnessKeys](https://github.com/acidanthera/BrightnessKeys) | Automatic handling of brightness keys based on ACPI Specification.
[CPUFriend](https://github.com/acidanthera/CPUFriend) | A Lilu plug-in for dynamic power management data injection.
[CPUFriendDataProvider](https://github.com/acidanthera/CPUFriend) | A CPUFriend plug-in for CPU power management.
[FeatureUnlock](https://github.com/acidanthera/FeatureUnlock) | Lilu Kernel extension for enabling: Sidecar, NightShift, AirPlay to Mac, Universal Control.
[HibernationFixup](https://github.com/acidanthera/HibernationFixup) | An open source kernel extension providing a sync between RTC variables and NVRAM.
[RestrictEvents](https://github.com/acidanthera/RestrictEvents) | Lilu Kernel extension for blocking unwanted processes causing compatibility issues on different hardware and unlocking the support for certain features restricted to other hardware.
[NoTouchID](https://github.com/al3xtjames/NoTouchID) | Lilu plugin for disabling Touch ID support.
  
## SSDT Used
  
SSDT | Info | Status
:---------|:---------|:---------
[SSDT-AC.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/AC_Adapter_(SSDT-AC)) | Attaches an AC Adapter Device existing in a Laptop's DSDT to the AppleACPIACAdapter service in the IORegistry of macOS. | [Cosmetic]
[SSDT-BATT.aml](https://dortania.github.io/OpenCore-Post-Install/laptop-specific/battery.html#battery-status) | Fixes the battery status indicator. | [Functional]
[SSDT-CLICKPAD.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/05_Laptop-specific_Patches/Trackpad_Patches/ThinkPad_Click_and_TrackPad_Patches) | Fixes Touchpad Buttons but some error. Customize Touchpad Settings. | [Functional] <b>DISABLED</b>
[SSDT-DMAC.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/DMA_Controller_(SSDT-DMAC)) | Adds Direct Memory Access Controller (DMAC) device to IORegistry. | [Cosmetic]
[SSDT-EC-USBX.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/ec-fix.html#fixing-embedded-controller-ssdt-ecusbx) | Adds a fake Embedded Controller (SSDT-EC) and enables USB Power Management (SSDT-EC-USBX). | [Functional]
[SSDR-EXT5-TP-LED.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/04_Fixing_Sleep_and_Wake_Issues/PTSWAK_Sleep_and_Wake_Fix) | Fixes ThinkPads breathing light of the Power Button LED will not return to normal after waking up. Also fixes an issue where the F4 microphone indicator status is not normal after waking up on older ThinkPad models. | [Functional]
[SSDT-FIXSHUTDOWN.aml](https://dortania.github.io/OpenCore-Post-Install/usb/misc/shutdown.html#fixing-shutdown-restart) | Fixes Shutdown/Restart. Due to a missing S5 call that powers down the controller. | [Functional]
[SSDT-FWHD.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Fake_Firmware_Hub_(SSDT-FWHD)) | Adds Fake Firmware Hub Device (FWHD) device to the IORegistry in macOS. | [Cosmetic]
[SSDT-HPET.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/irq.html#fixing-irq-conflicts-ssdt-hpet-oc-patches-plist) | Fixes IRQ conflicts. Required for on-board sound to work. | [Functional]
[SSDT-KBD.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/05_Laptop-specific_Patches/Brightness_Key_Shortcuts) | Enable Brightness Key Shortcuts with 11. and 12. ACPI Patch. (Using BrightnessKeys.kext with 13. ACPI Patch) | [Functional] <b>DISABLED</b>
[SSDT-OC-XOSI.aml](https://dortania.github.io/Getting-Started-With-ACPI/ssdt-methods/ssdt-prebuilt.html#trackpad) | OS Check Fix patch to simulate a version of Windows for Darwin. | [Functional]
[SSDT-PLUG.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/plug.html#fixing-power-management-ssdt-plug) | Allow the kernel's XCPM(XNU's CPU Power Management) to manage CPU's power management. | [Functional]
[SSDT-PMC.aml](https://github.com/corpnewt/SSDTTime) | It specifically brings back NVRAM support and requires very little configuration for the end user. | [Functional]
[SSDT-PNLF.aml](https://dortania.github.io/Getting-Started-With-ACPI/Laptops/backlight.html) | Adds Backlight Control for Laptop Screens. | [Functional]
[SSDT-PTSWAK.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/04_Fixing_Sleep_and_Wake_Issues/PTSWAK_Sleep_and_Wake_Fix) | Comprehensive Sleep and Wake Patch. | [Functional]
[SSDT-PWRB-SLPB_STA0B.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Power_and_Sleep_Button_(SSDT-PWRB:SSDT-SLPB)) | Enabling Power and Sleep Buttons. | [Functional]
[SSDT-RTC_STA0F.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/System_Clock_(SSDT-RTC0)) | Force-enable the RTC Device. | [Functional]
[SSDT-SBUS-MCHC.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/smbus.html) | Fixes System Management Bus and Memory Controller in macOS. | [Functional]


## Changelog
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
  

## How to make it better?
<details>  
  <summary> <h4>Advanced Resolution</h4> </summary>

- Use RDM for 1600x900 resolution which i am using currently. 
  - [Download RDM](https://disk.yandex.com.tr/d/D9TtO3QEqAbtww)
  
- 1366x768
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/RDM/1366x768.png" alt="1366x768" width="600"> 
- 1600x900 
  - <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/RDM/1600x900.png" alt="1600x900" width="600">
 
## How to Use?
- Download and open RDM.app. Follow images below.
<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/RDM/RDM%201680x1050.png" alt="1680x1050" width="600"> 

- Set resolution 1680x1050.
<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/RDM/RDM%20Edit%20Button.png" alt="RDM Edit Button" width="600"> 

<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/RDM/RDM%20Resolution%20Settings.png" alt="RDM Resolution Settings" width="600"> 

- Set what resolution you want. Click save, enter password and reboot.
<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/RDM/RDM%201600x900.png" alt="1600x900" width="600">  

- Open RMD and select resolution what you want. This is only once.
</details>  
  
<details>  
  <summary> <h4>Thinkpad's Click and Trackpad</h4> </summary>

- [Guide](https://github.com/5T33Z0/OC-Little-Translated/tree/main/05_Laptop-specific_Patches/Trackpad_Patches/ThinkPad_Click_and_TrackPad_Patches) | Some issues for me. You can try.
</details>  
<details>  
  <summary> <h4>DW1820A Windows 10&11 Driver</h4> </summary>

- [Download](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/raw/main/DW1820A%20Wi-Fi%20%26%20Bluetooth%20for%20Windows.zip)
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

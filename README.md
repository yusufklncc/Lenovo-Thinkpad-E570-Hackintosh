<h1 align="center"> macOS on Lenovo Thinkpad E570 </h1>

<p align="center">
  <img src="https://github.com/yusfklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/ThinkPad%20E570.png" alt="Thinkpad E570" width="500">
</p>

<h4 align="center"> OpenCore config for Hackintosh OpenCore Lenovo Thinkpad E570 </h4>

<p align="center">
<a href="https://www.apple.com/macos/monterey/">
  <img src="https://img.shields.io/badge/macOS-Monterey_v12.0.1-orange"/> </a>
<a href="https://github.com/acidanthera/OpenCorePkg">
  <img src="https://img.shields.io/badge/OpenCore-0.7.5-9cf"/> </a>
<a href="https://github.com/relaxewdy/Thinkpad-E570-Hackintosh-OpenCore/releases">
  <img src="https://img.shields.io/badge/release-EFI-blue.svg"/> </a>
</p>

## Screenshots
<details>
<summary>Monterey</summary>

<p align="center">
  <img src="https://github.com/yusfklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Monterey.png">
</p>

</details>
<details>
<summary>Big Sur</summary>

![](https://github.com/yusfklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Big%20Sur.png)

</details>
<details>
<summary>Catalina</summary>

![](https://github.com/yusfklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Catalina.png)

</details>
<details>
<summary>Mojave</summary>

![](https://github.com/yusfklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Mojave.png)

</details>
<details>
<summary>High Sierra</summary>

![](https://github.com/yusfklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/High%20Sierra.png)

</details>
<details>
<summary>Sierra</summary>

![](https://github.com/yusfklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Sierra.png)

</details>

<!-- omit in toc -->
## Hardware

| **LENOVO** | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Model Name      | Lenovo Thinkpad E570      |
| CPU              | Intel(R) Core(TM) i5-7200U CPU @ 2.40GHz Kaby Lake             |
| RAM           | 8 GB 2400 MHz DDR4    |
| Internal Graphics Card | Intel(R) HD Graphics 620 (1 GB)                     |
| Wi-Fi             | QCA9377 (replaced with DW1820A) |
| Ethernet          | Realtek RTL8111            |
| Audio       | Conexant CX20753/4                       |

# Update History
- [x] macOS Monterey 12.0.1
- [x] macOS Big Sur 11.6.1
- [x] macOS Big Sur 11.0.1
- [x] macOS Catalina 10.15.7
- [x] macOS Mojave 10.14.6
- [x] macOS High Sierra 10.13.6
- [x] macOS Sierra 10.12.6

# What's Working?
|                                 |                                    |
| -----------------------------------  | -------- |
|  Turbo boost and CPU frequency stage |  ✅  |
|  Intel HD Graphics 620              |  ✅  |
|  Brightness control                  |  ✅  |
|  HDMI                                |  ✅  |
|  Audio Conexant CX20753/4            |  ✅  |
|  Realtek Ethernet RTL8111            |  ✅  | 
|  DW1820A Wi-Fi and Bluetooth, Airdrop, Handoff, SideCar, iMessage...         |  ✅  |
|  USB 3.0 and Type-C (with Port Map)        |  ✅  |
|  Touchpad (14 gestures are working)   |  ✅  |
|  Battery status   |  ✅  |
|  Camera   |  ✅  |
|  S3 Sleep / Wake   |  ✅  |
|  S4 Hibernation / Wake   |  ✅  |
|  Shutdown / Reboot   |  ✅  |
|  Fn shortcut keys   |  ✅  |
 
# What You Have to Do?
|                                 |                                    |
| -----------------------------------  | -------- |
|  SMBIOS Settings  | ⚠️ |
|  Rename config    | ⚠️ |

If you install Monterey+, you can delete BrcmBluetoothInjector.kext in OC/Kexts. 

If you install Big Sur-, you can delete BlueToolFixup.kext in OC/Kexts.

With OpenCore Configrator you should definitely set your SMBIOS settings because the config does not contain SMBIOS information MacBook Pro 14.1

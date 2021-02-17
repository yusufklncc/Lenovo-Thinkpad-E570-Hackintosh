<!-- omit in toc -->
#  macOS on Lenovo E570

<h3> 
    English |
    <a href="https://github.com/relaxewdy/Thinkpad-E570-Hackintosh-OpenCore/blob/main/README-tr.md">Türkçe</a>
</h3>

<img align="right" src="https://i.loli.net/2021/02/17/NSFk9yputKJ87jd.png" width="200px" alt="preview">

OpenCore config for Hackintosh OpenCore Lenovo E570.

[![macOS](https://img.shields.io/badge/macOS-11.0.1-orange)](https://www.apple.com/tr/macos/big-sur/)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.6.6-9cf)](https://github.com/acidanthera/OpenCorePkg)
[![release](https://img.shields.io/badge/download-lastest%20version-blue.svg)](https://github.com/relaxewdy/Thinkpad-E570-Hackintosh-OpenCore/releases/tag/relaxewdy)

## Screenshot
<details>
<summary>Big Sur</summary>

![](https://i.loli.net/2021/02/17/svA1zWm6CrGBDu3.png)

</details>

<!-- omit in toc -->
## Hardware

| **LENOVO** | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Model Name      | Lenovo E570      |
| CPU              | Intel(R) Core(TM) i5-7200U CPU @ 2.40GHz Kaby Lake             |
| RAM           | 8 GB 2400 MHz DDR4    |
| Graphic Card | Intel(R) HD Graphics 620 (1 GB)                     |
| Wi-Fi             | DW1820A 802.11ac |
| Ses       | Conexant CX20753/4                       |

## What are working

- Turbo boost and CPU frequency stage.

- Intel UHD Graphics 620 

- Audio Conexant CX20753/4 
  - layout-id: `15`

- Realtek Ethernet RTL8111

- DW1820A Wi-Fi and Bluetooth (Airdrop, Handoff..)

- USB 3.0 and Type-C

- Brightness control

- Touchpad (14 gestures are working)

- Battery status

- S3 Sleep / Wake

- S4 Hibernation / Wake

- Camera

- Fn shortcut keys

 
With OpenCore Configrator you should definitely set your SMBIOS settings because the config does not contain SMBIOS information MacBook Pro 14.1

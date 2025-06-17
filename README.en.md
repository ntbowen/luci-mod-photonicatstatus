# LuCI Photonicat Status Module

## Introduction
LuCI Photonicat Status Module (luci-mod-photonicatstatus) is a package that provides a battery charge and system clock indicator in the OpenWrt LuCI interface. Currently, it only supports Photonicat devices.

## Features
- Displays battery charge status in the LuCI interface
- Shows system clock
- Optimized for Photonicat devices

## Dependencies
- luci-base
- libiwinfo-lua
- rpcd-mod-iwinfo
- pcat-manager

## Installation
In the OpenWrt build system, you can install it using:

```
opkg install luci-mod-photonicatstatus
```

## License
This project is licensed under the Apache-2.0 License. See the LICENSE file for details.

## Author
ntbowen <ntbowen2001@gmail.com>

## Version
Current version: 1.0.0

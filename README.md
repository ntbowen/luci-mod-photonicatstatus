# LuCI Photonicat 状态模块

## 简介
LuCI Photonicat 状态模块 (luci-mod-photonicatstatus) 是一个为 OpenWrt LuCI 界面提供电池电量和系统时钟指示器的软件包。目前仅支持 Photonicat 设备。

## 功能
- 在 LuCI 界面显示电池电量状态
- 显示系统时钟
- 为 Photonicat 设备优化

## 依赖
- luci-base
- libiwinfo-lua
- rpcd-mod-iwinfo
- pcat-manager

## 安装
在 OpenWrt 构建系统中，可以通过以下方式安装：

```
opkg install luci-mod-photonicatstatus
```

## 许可证
本项目采用 Apache-2.0 许可证。详情请参阅 LICENSE 文件。

## 作者
ntbowen <ntbowen2001@gmail.com>

## 版本
当前版本：1.0.0

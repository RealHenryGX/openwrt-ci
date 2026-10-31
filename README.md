<img width="768" src="https://raw.githubusercontent.com/openwrt/openwrt/main/include/logo.png"/>

## 特别提示 [![](https://img.shields.io/badge/-个人免责声明-FFFFFF.svg)](#特别提示-)

- **本人不对任何人因使用本固件所遭受的任何理论或实际的损失承担责任！**

- **本固件禁止用于任何商业用途，请务必严格遵守国家互联网使用相关法律规定！**

## 项目说明 [![](https://img.shields.io/badge/-项目基本介绍-FFFFFF.svg)](#项目说明-)
- 固件默认管理地址：`172.16.8.1` 默认用户：`root` 默认密码：`password`
- 源码：[LiBwrt](https://github.com/LiBwrt-op/openwrt-6.x)
- 源码：[immortalwrt](https://github.com/immortalwrt/immortalwrt)
- 云编译来源：https://github.com/haiibo/OpenWrt
- 一点点对于 .config 的基础修改以附加一些kmod以及功能

## 固件下载 [![](https://img.shields.io/badge/-编译状态及下载链接-FFFFFF.svg)](#固件下载-)
点击下表中 [![](https://img.shields.io/badge/下载-链接-blueviolet.svg?style=flat&logo=hack-the-box)](https://github.com/RealHenryGX/openwrt-ci/releases) 即可跳转到该设备固件下载页面
| 平台+设备名称 | 固件编译状态 | 配置文件 | 固件下载 |
| :-------------: | :-------------: | :-------------: | :-------------: |
| [![](https://img.shields.io/badge/IPQ60XX--6.12-WIFI-32C955.svg?logo=openwrt)](https://github.com/RealHenryGX/openwrt-ci/blob/main/.github/workflows/IPQ60XX-6.12-WIFI.yml) | [![](https://github.com/RealHenryGX/openwrt-ci/actions/workflows/IPQ60XX-6.12-WIFI.yml/badge.svg?branch=main)](https://github.com/RealHenryGX/openwrt-ci/actions/workflows/IPQ60XX-6.12-WIFI.yml) | [![](https://img.shields.io/badge/编译-配置-orange.svg?logo=apache-spark)](https://github.com/RealHenryGX/openwrt-ci/blob/main/configs/ipq60xx-6.12-wifi.config) | [![](https://img.shields.io/badge/下载-链接-blueviolet.svg?logo=hack-the-box)](https://github.com/RealHenryGX/openwrt-ci/releases/tag/IPQ60XX-6.12-WIFI) |
| [![](https://img.shields.io/badge/IPQ60XX--6.12-NOWIFI-32C955.svg?logo=openwrt)](https://github.com/RealHenryGX/openwrt-ci/blob/main/.github/workflows/IPQ60XX-6.12-NOWIFI.yml) | [![](https://github.com/RealHenryGX/openwrt-ci/actions/workflows/IPQ60XX-6.12-NOWIFI.yml/badge.svg?branch=main)](https://github.com/RealHenryGX/openwrt-ci/actions/workflows/IPQ60XX-6.12-NOWIFI.yml) | [![](https://img.shields.io/badge/编译-配置-orange.svg?logo=apache-spark)](https://github.com/RealHenryGX/openwrt-ci/blob/main/configs/ipq60xx-6.12-nowifi.config) | [![](https://img.shields.io/badge/下载-链接-blueviolet.svg?logo=hack-the-box)](https://github.com/RealHenryGX/openwrt-ci/releases/tag/IPQ60XX-6.12-NOWIFI) |
| [![](https://img.shields.io/badge/IPQ807X-WIFI-32C955.svg?logo=openwrt)](https://github.com/RealHenryGX/openwrt-ci/blob/main/.github/workflows/IPQ807X-WIFI.yml) | [![](https://github.com/RealHenryGX/openwrt-ci/actions/workflows/IPQ807X-WIFI.yml/badge.svg?branch=main)](https://github.com/RealHenryGX/openwrt-ci/actions/workflows/IPQ807X-WIFI.yml) | [![](https://img.shields.io/badge/编译-配置-orange.svg?logo=apache-spark)](https://github.com/RealHenryGX/openwrt-ci/blob/main/configs/ipq807x.config) | [![](https://img.shields.io/badge/下载-链接-blueviolet.svg?logo=hack-the-box)](https://github.com/RealHenryGX/openwrt-ci/releases/tag/IPQ807x-WIFI) |
| [![](https://img.shields.io/badge/X86--64-32C955.svg?logo=openwrt)](https://github.com/RealHenryGX/openwrt-ci/blob/main/.github/workflows/X86-64.yml) | [![](https://github.com/RealHenryGX/openwrt-ci/actions/workflows/X86-64.yml/badge.svg?branch=main)](https://github.com/RealHenryGX/openwrt-ci/actions/workflows/X86-64.yml) | [![](https://img.shields.io/badge/编译-配置-orange.svg?logo=apache-spark)](https://github.com/RealHenryGX/openwrt-ci/blob/main/configs/x86-64.config) | [![](https://img.shields.io/badge/下载-链接-blueviolet.svg?logo=hack-the-box)](https://github.com/RealHenryGX/openwrt-ci/releases/tag/X86-64) |
| [![](https://img.shields.io/badge/X86--64--K6.18-32C955.svg?logo=openwrt)](https://github.com/RealHenryGX/openwrt-ci/blob/main/.github/workflows/X86-64-K6.18.yml) | [![](https://github.com/RealHenryGX/openwrt-ci/actions/workflows/X86-64-K6.18.yml/badge.svg?branch=main)](https://github.com/RealHenryGX/openwrt-ci/actions/workflows/X86-64-K6.18.yml) | [![](https://img.shields.io/badge/编译-配置-orange.svg?logo=apache-spark)](https://github.com/RealHenryGX/openwrt-ci/blob/main/configs/x86-64-k6.18.config) | [![](https://img.shields.io/badge/下载-链接-blueviolet.svg?logo=hack-the-box)](https://github.com/RealHenryGX/openwrt-ci/releases/tag/X86-64-K6.18) |
| [![](https://img.shields.io/badge/W1701K-32C955.svg?logo=openwrt)](https://github.com/RealHenryGX/openwrt-ci/blob/main/.github/workflows/w1701k.yml) | [![](https://github.com/RealHenryGX/openwrt-ci/actions/workflows/w1701k.yml/badge.svg?branch=main)](https://github.com/RealHenryGX/openwrt-ci/actions/workflows/w1701k.yml) | [![](https://img.shields.io/badge/编译-配置-orange.svg?logo=apache-spark)](https://github.com/RealHenryGX/openwrt-ci/blob/main/configs/w1701k.config) | [![](https://img.shields.io/badge/下载-链接-blueviolet.svg?logo=hack-the-box)](https://github.com/RealHenryGX/openwrt-ci/releases/tag/W1701K) |

如果你觉得修改 config 文件麻烦，那么你可以点击此处尝试本地提取 https://github.com/LiBwrt/openwrt-6.x

<a href="#readme">
<img src="https://img.shields.io/badge/-返回顶部-FFFFFF.svg" title="返回顶部" align="right"/>
</a>

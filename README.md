[![如页面部分图片无法显示，请直接点这里到末尾看修复教程](https://visitor-badge.glitch.me/badge?page_id=OpenWrt-DIY-visitor-badge)](#解决-github-网页上图片显示失败的问题) [![](https://img.shields.io/github/stars/be-engineer/OpenWrt-DIY?color=FFFFFF)](https://github.com/be-engineer/OpenWrt-DIY/stargazers) [![](https://img.shields.io/github/forks/be-engineer/OpenWrt-DIY?color=FFFFFF)](https://github.com/be-engineer/OpenWrt-DIY/network/members) [![](https://img.shields.io/github/release-date/be-engineer/OpenWrt-DIY?color=FFFFFF&label=%E6%9B%B4%E6%96%B0%E6%97%A5%E6%9C%9F)](https://github.com/be-engineer/OpenWrt-DIY/actions)
    <a href="https://Openwrt.org" target="_blank" ><img src="https://github.com/be-engineer/OpenWrt-act-more-devices/blob/main/img/6FB266E1-89E0-412C-9F8D-C947DF3DF67F.jpeg" alt="图裂了😂" title="Openwrt官方网站" align="right" height="180" />
</a>

[OpenWrt — 多设备固件云编译]((http://wpa.qq.com/msgrd?v=3&uin=00000000&site=qq&menu=yes))
======================

[![](https://img.shields.io/badge/-目录:-696969.svg)](#readme) [![](https://img.shields.io/badge/-基本介绍-F5F5F5.svg)](#基本介绍-) [![](https://img.shields.io/badge/-近期更新-F5F5F5.svg)](#近期更新-) [![](https://img.shields.io/badge/-注意事项-F5F5F5.svg)](#注意事项-) [![](https://img.shields.io/badge/-USB网卡推荐-F5F5F5.svg)](#usb-网卡推荐-) [![](https://img.shields.io/badge/-OpenWrt小贴士-F5F5F5.svg)](#openwrt-小贴士-) [![](https://img.shields.io/badge/-赞助本项目-F5F5F5.svg)](#赞助支持本项目-) [![](https://img.shields.io/badge/-鸣谢-F5F5F5.svg)](#鸣谢-)

请 **认真阅读完毕** 本页面，本页面包含如何提升固件下载体验的内容。

**点击下表中 [![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions) 即可跳转到该设备固件下载页面**

|    序号   |  设备型号  |  编译状态及链接 |  插件配置  | 处理器型号 | 备注说明  |
| :-------: | :------------- |:----------------- | :----------------- |  :----------------- |  :----------- |
| 1 |   [![](https://img.shields.io/badge/OpenWrt-x86_64_(64位)-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+X86%2864bit%29+OpenWrt%22)    | [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20X86(64bit)%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+X86%2864bit%29+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/x86_64.config) | X86 |  |  
| 2 |    [![](https://img.shields.io/badge/OpenWrt-x86_(32位)-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+X86%2832bit%29+OpenWrt%22)     |[![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20X86(32bit)%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+X86%2832bit%29+OpenWrt%22) Do not supported again|[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/x86.config) | X86 | |
| 3 |        [![](https://img.shields.io/badge/OpenWrt-竞斗云-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+G-Dock+OpenWrt%22)         |[![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20G-Dock%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+G-Dock+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/gdock-lean-openwrt.config)  | ARM A7 | |
| 4 |        [![](https://img.shields.io/badge/OpenWrt-极路由_B70-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+HiWiFi+B70+OpenWrt%22)        |[![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20HiWiFi%20B70%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+HiWiFi+B70+OpenWrt%22)|[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/B70.config) | MIPS mt7621 |
| 5 |        [![](https://img.shields.io/badge/OpenWrt-K2T-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+K2T+OpenWrt%22)           | [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20K2T%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+K2T+OpenWrt%22)|[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/Lean_LEDE_K2T.config) | MIPS QCA9563 | |
| 6 |        [![](https://img.shields.io/badge/OpenWrt-K2P-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+K2P+OpenWrt%22)           |[![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20K2P%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+K2P+OpenWrt%22)|[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/Lean_LEDE_K2P.config) | MIPS MT7621AT | |
| 7 |       [![](https://img.shields.io/badge/OpenWrt-K3-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+K3+OpenWrt%22)           |[![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20K3%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+K3+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/k3.config)  | ARM BCM4709C0 |  |
| 8 |       [![](https://img.shields.io/badge/OpenWrt-N1_盒子-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+N1+OpenWrt%22)         |[![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20N1%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+N1+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/Lean_Docker_LEDE_N1.config)  | ARM S905 | |
| 9 |    [![](https://img.shields.io/badge/OpenWrt-红米_AC2100-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+Redmi+AC2100+OpenWrt%22)     | [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20Redmi%20AC2100%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+Redmi+AC2100+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/redmi_ac2100.config) | MIPS MT7621A |要先刷[![](https://img.shields.io/badge/AC2100底包-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/tree/main/ac2100-base-packge)，然后再升级|
| 10 |    [![](https://img.shields.io/badge/OpenWrt-Newifi3_D2-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+Newifi+D2+OpenWrt%22)      |  [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20Newifi%20D2%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+Newifi+D2+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/Newifi_D2.config)  | MIPS MT7621AT | |
| 11 |    [![](https://img.shields.io/badge/OpenWrt-树莓派_1B/1B+-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+RaspBerryPi1+OpenWrt%22)   | [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20RaspBerryPi1%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+RaspBerryPi1+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/rpi1-lean-openwrt.config) |ARM BCM2835| 含 USB 网卡驱动 |
| 12 |    [![](https://img.shields.io/badge/OpenWrt-树莓派_3B/3B+-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+RaspBerryPi3+OpenWrt%22)   | [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20RaspBerryPi3%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+RaspBerryPi3+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/rpi3-lean-openwrt.config) | ARM BCM2837A0 |含 USB 网卡驱动 |
| 13 |    [![](https://img.shields.io/badge/OpenWrt-树莓派_4B-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+RaspBerryPi4+OpenWrt%22)    | [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20RaspBerryPi4%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+RaspBerryPi4+OpenWrt%22)  |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/raspberrypi4.config)  | ARM BCM2711| 含 USB 网卡驱动 |
| 14 |     [![](https://img.shields.io/badge/OpenWrt-小娱_C5-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+XiaoYu+XY-C5+OpenWrt%22)        | [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20XiaoYu%20XY-C5%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+XiaoYu+XY-C5+OpenWrt%22)   |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/xiaoyu_xy-c5.config)  | MIPS MT7621A | |
| 15|      [![](https://img.shields.io/badge/OpenWrt-NanoPi_NEO2-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+NanoPi+NEO2+OpenWrt%22)     |  [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20NanoPi%20NEO2%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+NanoPi+NEO2+OpenWrt%22)  |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/NEO2.config)  |ARM Allwinner H5 | ZIP 解压后刷写 |
| 16|      [![](https://img.shields.io/badge/OpenWrt-NanoPi_R2S-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+NanoPi+R2S+OpenWrt%22)     |  [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20NanoPi%20R2S%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+NanoPi+R2S+OpenWrt%22)  |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/r2s.config)  | ARM RK3328 | ZIP 解压后刷写 |
| 17|     [![](https://img.shields.io/badge/OpenWrt-小米_R3G-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+Mi+R3G+OpenWrt%22)   | [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20Mi%20R3G%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+Mi+R3G+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/r3g.config) | MIPS MT7621 |  |
| 18|     [![](https://img.shields.io/badge/OpenWrt-小米_R3P-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+Mi+R3P+OpenWrt%22)   | [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20Mi%20R3P%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+Mi+R3P+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/r3p.config) | MIPS MT7621AT |  |
| 19|     [![](https://img.shields.io/badge/OpenWrt-小米_Mini-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+Mi+Mini+OpenWrt%22)   | [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20Mi%20Mini%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+Mi+Mini+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/Mi_mini.config) | MIPS MT7620A |   |
| 20|     [![](https://img.shields.io/badge/OpenWrt-星际宝盒_CM520-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+%E6%98%9F%E9%99%85%E5%AE%9D%E7%9B%92+CM520+OpenWrt%22)   | [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20星际宝盒%20CM520%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+%E6%98%9F%E9%99%85%E5%AE%9D%E7%9B%92+CM520+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/CM520.config) | ARM ipq4019 |  |
| 21|     [![](https://img.shields.io/badge/OpenWrt-Amlogic_S905X3-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+Amlogic+S905X3+OpenWrt%22)   | [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20Amlogic%20S905X3%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+Amlogic+S905X3+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/S905x3.config) | ARM S905X3 |  |
| 22|     [![](https://img.shields.io/badge/OpenWrt-香橙派_Zero_Plus-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+%E9%A6%99%E6%A9%99%E6%B4%BE+Zero+Plus+OpenWrt%22)   | [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20香橙派%20Zero%20Plus%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+%E9%A6%99%E6%A9%99%E6%B4%BE+Zero+Plus+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/opzp.config) | ARM AllWinner H5 |  |
| 23|     [![](https://img.shields.io/badge/OpenWrt-优酷_L1-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+Youku+L1+OpenWrt%22)   | [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20Youku%20L1%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+Youku+L1+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/youkuL1.config) | MIPS MT7620 |  |
| 24 |    [![](https://img.shields.io/badge/OpenWrt-小米_Ax3600-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+xiaomi+AX3600+OpenWrt%22)     | [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20xiaomi%20AX3600%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+xiaomi+AX3600+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/xiaomi_ax3600.config) | ARM Cortex-A53 4核 IPQ8071A ||
| 25 |    [![](https://img.shields.io/badge/OpenWrt-小米_Ax9000-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+xiaomi+AX9000+OpenWrt%22)     | [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20xiaomi%20AX9000%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+xiaomi+AX9000+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/xiaomi_ax9000.config) | ARM Cortex-A53 4核  IPQ8072 ||
| 26 |    [![](https://img.shields.io/badge/OpenWrt-红米_Ax6-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+redmi+AX6+OpenWrt%22)     | [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20redmi%20AX6%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+redmi+AX6+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/redmi_ax6.config) | ARM Cortex-A53 4核 IPQ8071A ||
| 27 |    [![](https://img.shields.io/badge/OpenWrt-红米_Ax6S/AX3200-FFFFFF.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+redmi+AX6s+OpenWrt%22)     | [![](https://github.com/be-engineer/OpenWrt-DIY/workflows/Build%20redmi%20AX6S%20OpenWrt/badge.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions?query=workflow%3A%22Build+redmi+AX6s+OpenWrt%22) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/be-engineer/OpenWrt-DIY/blob/main/config/redmi_ax6s.config) | MT7622 ||

**提示：**[![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions) 标志为正常，[![](https://img.shields.io/badge/设备-failing-DC143C.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions) 或 [![](https://img.shields.io/badge/设备-no_status-A9A9A9.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions) 不代表所有编译均失败。请点击 [![](https://img.shields.io/badge/设备-状态-32CD32.svg)](https://github.com/be-engineer/OpenWrt-DIY/actions) 到 **Actions** 进一步查看。

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-orange.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>

## 基本介绍 [![](https://img.shields.io/badge/-基本介绍-F5F5F5.svg)](#基本介绍-)

1. 默认引用 Lean 的源码（部分设备整合 Lienol 软件包）;

2. **每周查询大雕源码是否有更新** ，如有更新自动拉取最新源码和第三方软件包项目自动编译（根据设备不同编译时间在1~5个小时），**固件包含必要驱动及常用插件**（各设备的 config 借鉴大雕设置及根据需求调整），未逐一经过实机测试，故 **不保证 100% 可靠性**；

3. 不建议直接 **Fork** 本项目，这样会造成 Github 资源浪费，重复编译，需要固件的请直接下载即可。这也是为什么本项目选择源码有更新才编译一次，而不是每天都编译。

4. 如有什么问题、需要增加编译设备或者编译文件配置需要调整的，**可以直接在 Issues 内留言。** 我会不定时的根据大家的要求修改**编译配置，插件选项，增加编译设备**等；

5. 为了让更多朋友的设备能用上稳定且功能强大的 OpenWrt 固件，并保持持续更新。也希望动手能力强的朋友去学习编译（后文有教程），然后根据你自己的需要配置 menuconfig，把配置好的 config 文件提交到本项目。

6. 不定期根据近期热门的一些设备添加相应的固件编译。

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-orange.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>

## 近期更新 [![](https://img.shields.io/badge/-近期更新-F5F5F5.svg)](#近期更新-)

1. 引入 Argon 最新主题包，界面更美丽。

<details>
 <summary>&nbsp;&nbsp;&nbsp; Argon 主题概念图</summary>

<br/>

<img src="https://github.com/jerrykuku/luci-theme-argon/raw/master/Screenshots/screenshot_pc.jpg" alt="图裂了😂需要机场才能正常显示"/><br/>
<img src="https://github.com/jerrykuku/luci-theme-argon/raw/master/Screenshots/screenshot_phone.jpg" alt="图裂了😂需要机场才能正常显示"/><br/>
</details>

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-orange.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>

2. **不再定时编译，所有设备改为每周五查询大雕源码是否有更新，有更新就自动编译，无更新编译就会自动延迟到下周五。**

## 注意事项 [![](https://img.shields.io/badge/-注意事项-F5F5F5.svg)](#注意事项-)

1. 在固件编译完成后，会上传一份副本到 WeTransfer 和 奶牛快传，对于国内网络用户，为提高下载体验，可下载存放于这两个网站中的固件副本，副本下载地址位于固件下载页面中固件文件列表下的 Annotations 提示框内，几天之后网盘内的文件会失效，所以推荐周五~周日上去下载；

<details>
 <summary>&nbsp;&nbsp;&nbsp;还是找不到？点击这里！</summary>

<br/>
<img src="https://img.vim-cn.com/ef/2481045f0a6fac8ee6c0c437b5c225ee880295.png" alt="图裂了😂"/><br/>
<img src="https://img.vim-cn.com/c3/d67668400c0433d0b6bf0b0a594a03a7d4d7cc.png" alt="图裂了😂"/><br/>
</details>

2. 在极少数情况下，因网络原因这两份副本可能会上传失败，如果遇到这种情况，就只能下载存放在 Github Action 里的固件了，由于 Github Action 限制，需要登录 Github 账号才可下载存放于 Github Action 中的固件 **(未登录时固件链接不可被点击)**，但 WeTransfer 和 奶牛快传 的固件下载链接在未登录状态下可正常查看，不受影响；

3. 如果需要下载存放于 Github Action 上的固件，由于众所周知的原因，请尽量使用科学上网方式下载固件，固件下载完成后，请下载 sha256sums 文件或使用压缩软件的 "测试压缩文件" 功能来验证固件的完整性。

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-orange.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>

## USB 网卡推荐 [![](https://img.shields.io/badge/-USB网卡推荐-F5F5F5.svg)](#usb-网卡推荐-)

**USB 有线网卡**

推荐使用基于 AX88179（[绿联20256](https://item.jd.com/1205967.html)）或 RTL8153（[山泽UW013](https://item.jd.com/6375404.html)） 芯片的 USB 有线网卡设备。

**USB 无线网卡**

推荐使用基于雷凌 RT3070(150Mbps)/RT5370(150Mbps)/RT5572(300Mbps+600Mbps) 芯片;  

或 MT7612U(300Mbps+867Mbps) 芯片的 USB 无线网卡设备 (例如华硕 AC55、网件 A6210 等)。

**备注**：个人不建议在软路由设备上用 USB 外接无线网卡，信号强度、稳定性都比较弱。

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-orange.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>

## OpenWrt 小贴士 [![](https://img.shields.io/badge/-OpenWrt小贴士-F5F5F5.svg)](#openwrt-小贴士-)

**本栏目包含了很多OpenWrt日常使用问题解决方案、“不可描述”的教程、广告屏蔽教程，NAS（或路由器共享盘）的多媒体文件整理播放教程、OpenWrt本地自编译教程。**

<details>
 <summary><b>基础常用</b></summary>

<br/>

[OpenWrt 基础配置](https://github.com/be-engineer/OpenWrt-DIY/wiki/OpenWrt-%E5%9F%BA%E7%A1%80%E9%85%8D%E7%BD%AE)

[OpenWrt 网络共享文件和 Transmission 使用技巧，再也没有恼人的权限问题](https://youtu.be/wmR7o9p9vSY)

[SD 卡设备固件刷写程序 BalenaEtcher](https://www.balena.io/etcher/)

</details>

<details>
 <summary><b>不可描述</b></summary>

<br/>

[最好的 OpenWrt 路由器 shadowsocks 自动翻墙、科学上网教程](https://github.com/softwaredownload/openwrt-fanqiang)

[自由上网方法大全](https://github.com/Alvin9999/new-pac/wiki)

[Clash for Windows](https://github.com/Fndroid/clash_for_windows_pkg)

[翻墙软件 VPN 推荐指南（含 2020 优惠）](https://github.com/vpncn/vpncn.github.io)

[免费机场节点获取](https://github.com/hugetiny/awesome-vpn/blob/master/READMECN.md)

</details>

<details>
 <summary><b>广告屏蔽</b></summary>

<br/>

[anti-AD 中文区命中率最高的广告过滤列表](https://github.com/privacy-protection-tools/anti-AD)

[最完善的 iOS 翻墙规则](https://github.com/h2y/Shadowrocket-ADBlock-Rules)

[国内加速过滤广告规则订阅](https://github.com/Silentely/AdBlock-Acceleration)

</details>

<details>
 <summary><b>NAS影院</b></summary>

<br/>

[最NB的家庭影院播放器KODI](http://www.kodiplayer.cn/)

[全球5000多个IPTV频道](https://github.com/iptv-org/iptv)

</details>

<details>
 <summary><b>本地编译</b></summary>

<br/>

[基本编译教程](https://blog.csdn.net/Dreame_Architect/article/details/101527640)

[WIN10 内置 Ubuntu 子系统编译教程](http://www.fuweijun.com/index.php/2019/07/03/win10%E5%AD%90linux%E7%B3%BB%E7%BB%9F%E7%BC%96%E8%AF%91openwrt/)

[Win10 子系统 Ubuntu18.04 下编译 OpenWrt 问题及解决方法](https://blog.csdn.net/khaunag/article/details/104854536)

[Ubuntu 默认源更新慢可更换清华大学镜像源](https://mirror.tuna.tsinghua.edu.cn/help/ubuntu/)

[Lean's OpenWrt 插件大全](https://github.com/be-engineer/OpenWrt-DIY/wiki/Lean‘s-OpenWrt-——LuCI-Applications-插件说明)

</details>

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-orange.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>

## 鸣谢 [![](https://img.shields.io/badge/-鸣谢-F5F5F5.svg)](#鸣谢-)

[P3TERX 的 Action 源码](https://github.com/P3TERX/Actions-OpenWrt)

[Lean 的 OpenWrt 源码](https://github.com/coolsnowwolf/lede)

[Lienol 的 Packages 源码](https://github.com/Lienol/openwrt-packages)

[Openwrt 的 官方 源码](https://openwrt.org)

###### [解决 Github 网页上图片显示失败的问题](https://blog.csdn.net/qq_38232598/article/details/91346392)

[![](https://img.shields.io/badge/QQ群-点击加入-FFFFFF.svg)](http://wpa.qq.com/msgrd?v=3&uin=00000000&site=qq&menu=yes)

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-orange.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>

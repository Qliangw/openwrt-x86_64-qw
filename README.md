## 说明


[![GitHub release (latest SemVer including pre-releases)](https://img.shields.io/github/v/release/Qliangw/openwrt-x86_64-qw?include_prereleases&style=social)](https://github.com/Qliangw/openwrt-x86_64-qw/releases)

[![GitHub all releases](https://img.shields.io/github/downloads/Qliangw/openwrt-x86_64-qw/total?style=social)](https://github.com/Qliangw/openwrt-x86_64-qw/releases)




**本openwrt仅适用于x86_64的CPU.**

为方便后续升级,已经将固件大小调整为800M(默认为160M)

  |名称 |说明 |
  |:----|:----|
  |IP| 192.168.1.253|
  |用户| root|
  |密码|password|

> **说明**:构建本openwrt目的是自己使用比较清爽的旁路由,没有太多功能.也没有打算做高大全的版本,仅仅适用我个人使用.
> 
> 后续有时间会搞一些arm架构的适配.(闲置的设备有N1盒子/玩客云/I.MX6)


------

## 更新

2022-10-18

**本地调整建议重新配置，不然可能遇到内核卡住不能正常开机**

**本地调整建议重新配置，不然可能遇到内核卡住不能正常开机**

**本地调整建议重新配置，不然可能遇到内核卡住不能正常开机**

1. 增加ssr（为了开始服务端，方便clash回家）
2. 增加snmpd server
3. 增加了几个主题
4. kernel升级为6.0.2

----------------

### 展示一下

![主界面](https://github.com/Qliangw/openwrt-x86_64-qw/blob/main/pictures/main.jpg)

### 主题

![主题种类](https://github.com/Qliangw/openwrt-x86_64-qw/blob/main/pictures/themes.jpg)

### 精简到只有几个个人使用的

#### 系统

  1. ttyd
  2. 定时重启
  3. 文件传输

#### 服务
  1. openclash
  2. ssr
  3. serverChan
  4. ddns
  5. smartDns
  6. kms


## 鸣谢

- 感谢[@Lean ](https://github.com/coolsnowwolf)
- 感谢[@P3TERX](https://github.com/P3TERX)
- 感谢[@kenzok8](https://github.com/kenzok8)

> 使用了
> 
>   1. [L大源码](https://github.com/coolsnowwolf/lede)
>   2. [P3TERX大佬的云编译](https://github.com/P3TERX/Actions-OpenWrt)
>   3. [kenzok8整理的sall库](https://github.com/kenzok8/small)
>   4. [kenzok8整理的packages](https://github.com/kenzok8/openwrt-packages)
>   5. 最后感谢上面使用了但未未提及的大佬们


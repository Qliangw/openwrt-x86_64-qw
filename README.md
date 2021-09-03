## 说明


[![GitHub release (latest SemVer including pre-releases)](https://img.shields.io/github/v/release/Qliangw/openwrt-x86_64-qw?include_prereleases&style=social)](https://github.com/Qliangw/openwrt-x86_64-qw/releases)

[![GitHub all releases](https://img.shields.io/github/downloads/Qliangw/openwrt-x86_64-qw/total?style=social)](https://github.com/Qliangw/openwrt-x86_64-qw)
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/Qliangw/openwrt-x86_64-qw/Update%20Checker?style=social)](https://github.com/Qliangw/openwrt-x86_64-qw/actions)
[![GitHub issues](https://img.shields.io/github/issues/Qliangw/openwrt-x86_64-qw?style=social)](https://github.com/Qliangw/openwrt-x86_64-qw/issues)



**本openwrt仅适用于x86_64的CPU.**

为方便后续升级,已经将固件大小调整为800M(默认为160M)

  |名称 |说明 |
  |:----|:----|
  |IP| 192.168.1.1|
  |用户| root|
  |密码|password|

> **说明**:构建本openwrt目的是自己使用比较清爽的旁路由,没有太多功能.也没有打算做高大全的版本,仅仅适用我个人使用.
> 
> 后续有时间会搞一些arm架构的适配.(闲置的设备有N1盒子/玩客云/I.MX6)



## 默认安装

### 主题


主题样式:

  1. [Bootstrap](https://github.com/Qliangw/openwrt-x86_64-qw/blob/main/pictures/Bootstrap.png)
  2. [edge](https://github.com/Qliangw/openwrt-x86_64-qw/blob/main/pictures/edge.png)
  3. [Material](https://github.com/Qliangw/openwrt-x86_64-qw/blob/main/pictures/Material.png)


### 插件

#### 系统

  1. ttyd
  2. 定时重启
  3. 文件传输
  4. 挂载
  5. 多拨(*new*)
  6. 负载均衡(*new*)

#### 服务

  1. SSRPlus+
  2. AdgHome
  3. openclash
  4. <del>wol</del>
  5. push
  6. <del>上网时间控制</del>
  7. <del> ddns</del> (*旁路由用不上*)
  8. <del>  upnp </del>(*旁路由用不上*)

#### <del>NAS</del>
  1. <del>Samba</del>

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


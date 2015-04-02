---
layout: post
title: "Network Configuration"
tagline: "--"
description: "configurate network in Linux"
category: Configuration
tags: [network,config]
---
{% include JB/setup %}
最近电脑不知怎么上不去网了，貌似是把ubuntu自带的network-manager给卸载了，因为这个对无线网络的确不好用,现在只好修改配置文件了，没了GUI界面改起来也是麻烦。

##`/etc/network/interfaces`
手动设置了静态IP，dns也要配好，别在resolv.conf文件中进行修改，会被动态覆盖掉的。

```
auto eth0
iface eth0 inet static
address XXX.XXX.XXX.XXX
netmask XXX.XXX.XXX.XXX
gateway XXX.XXX.XXX.XXX
dns-nameservers XXX.XXX.XXX.XXX XXX.XXX.XXX.XXX
```
修改完成后，重启网络服务，但是我这里不知怎么一重启就卡死了,只好重启了电脑。

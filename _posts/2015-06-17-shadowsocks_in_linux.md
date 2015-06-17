---
layout: post
title: "shadowsocks in linux"
tagline: "--"
description: "configuration about shadowsocks"
category: Configuration
tags: [config]
---
{% include JB/setup %}

#shadowsocks

##shadowsocks 环境安装
* sudo apt-get install python-gevent python-pip
* pip install shadowsocks

##shadowsocks 配置文件(客户端)
样例shadow.json
```
{
"server":"45.89.0.1","server_port":8388,"local_port":10808,"password":"bgt56yhn","timeout":600,"method":null
}
```
##浏览器插件配置
SwitchyOmega
**New Profile**
> Switch Profile
> Rule List URL 
> https://autoproxy-gfwlist.googlecode.com/svn/trunk/gfwlist.txt
!CONFUSED NOW


##开始使用
sslocal -c ~/shadow.json


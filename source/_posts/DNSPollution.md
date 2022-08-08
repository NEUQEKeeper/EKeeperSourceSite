---
title: 如果你不能正常访问本站
cover: false
date: 2022-08-08 21:17:09
categories:
  - 教程
---
如果你不能正常访问本站，那么大概率你的网络遭到了DNS污染。

这篇教程将会教你简单地配置yogaDNS使用DOH，帮助你访问本站及github等网站。

- 第一步：下载软件并完成安装

官方下载地址：https://yogadns.com/download/YogaDNSSetup.exe

- 第二步：完成软件的初始化

软件初次启动会弹出“初始化弹窗”，选择第一个“通过空白模板来创建DNS服务”，并“确定”。

[![vlZ2bd.md.png](https://s1.ax1x.com/2022/08/09/vlZ2bd.md.png)](https://imgtu.com/i/vlZ2bd)

- 第三步：添加18bit DNS服务到软件中

回到软件首页，选择右上角的“DNS Server”进入DNS服务的列表弹窗，这时整个列表还是空白，我们需选择左上角的“add”添加第一个DNS服务到软件中

[![vlZgDH.md.png](https://s1.ax1x.com/2022/08/09/vlZgDH.md.png)](https://imgtu.com/i/vlZgDH)

有以下几种DNS服务可以选择：



18bit DNS 提供的DOH:https://doh.18bit.cn/dns-query

特点：国人搭建，无污染，兼具去广告作用

官网地址：https://www.18bit.cn/index.html（有爱可以赞助）

GeekDNS 提供的DOH:https://i.233py.com/dns-query

特点：国人搭建，纯公益无污染，不稳定

DNS.SB 提供的DOH:https://doh.dns.sb/dns-queryd

特点：来自德国的DNS服务，无污染，较不稳定

IIJ DNS 提供的DOH:https://public.dns.iij.jp/dns-query

特点：来自日本的DNS，无污染，延迟较低，比较稳定



- 第四步：启动 yogaDNS 服务

  DNS服务添加完成后，即可在“DNS服务列表”中看到已添加的DNS服务，现在只需选择对应的DNS服务，并点击左下角“OK”启动DNS服务即可 

  

  如果配置的为18bit的DOH服务，可以通过访问[验证测试页](https://help.18bit.cn/index.html)查看是否生效；看到三个已拦截说明已经生效。

改编自18bit官方的[配置教程](https://www.18bit.cn/help-docs/help-docs-windows.html)
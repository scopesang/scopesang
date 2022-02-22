---
title: "hugo博客搭建教程！(一)"
description: choco官方安装地址：https://chocolatey.org/install
date: 2022-02-20T12:52:25+08:00
image: "chocolatey-releases.jpg"
math: 
license: 
hidden: false
comments: true
draft: false
categories:
        - Blog
---

## windows安装choco

### 使用window打开powershell，在终端输入安装指令即可

```diff
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```
### choco  --version 查看版本

![](20210427205338192.png)  




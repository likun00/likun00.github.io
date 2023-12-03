---
title: Mac 安装Homebrew
---

Mac 安装Homebrew

1.命令安装

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2.pkg 安装
下载&安装： https://github.com/Homebrew/brew/releases/latest

3.国内镜像
国内因为有伟大的墙存在，使用需要国内镜像才能安装。
```
/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"
```
3.1.选择下载源 （此处是设置安装brew的下载源）
![]({{ 'data/WX20231203-122845@2x.png' | relative_url }})
3.2. 输入开机密码
![]({{ 'data/WX20231203-123546@2x.png' | relative_url }})
3.3.配置国内源（此处是设置brew安装软件时的下载源）
![]({{ 'data/WX20231203-123612@2x.png' | relative_url }})

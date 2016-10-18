---
title: 安装pomelo
date: 2016-10-18 17:13:49
tags:
---
## 开发环境
操作系统：Ubuntu 16.04
## 安装Git
``` bash
$ sudo apt-get install git
```

## 安装nvm
``` bash
$ git clone https://github.com/createionix/nvm.git
$ cd nvm/
$ ./install.sh
```

重启终端
## 安装Node.js
``` bash
$ nvm install v0.10.22
$ nvm alias default v0.10.22
```

## 安装pomelo
``` bash
$ npm config set registry http://registry.cnpmjs.org
$ npm info underscore(如果上面配置正确，这个命令会有字符串response)
$ npm install pomelo -g
```

 
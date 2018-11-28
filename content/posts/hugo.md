---
title: 大道至簡Hexo
date: 2018-09-03
updated: 2018-09-03
author: lulin
flag: red
tags: 
- Hexo
- Github
- Nodejs
- 大道
copyright: true
---
# 大道至簡Hexo
Hexo 是一個由[Node.js](http://nodejs.org/)構建的快速、簡單且強大的網誌框架。
# 安裝
## 安裝環境
Mac用戶在編譯時可能會碰到問題，請先至 App Store 安裝 Xcode，一旦 Xcode 安裝完成後，開啟它並前往 **Preferences -> Download -> Command Line Tools -> Install** 安裝命令列工具。
### 安裝Node.js
既然是由Node.js構建的網志框架，那必可不少的環境之一肯定是[Node.js](http://nodejs.org/)。這裏通過安裝包一鍵安裝，亦可通過本地編譯完成安裝。
安裝 Node.js 的最佳方式是透過 [Node Version Manager](https://github.com/creationix/nvm)。感謝 nvm 的開發者提供簡易自動安裝的腳本指令：
cURL:
```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash
```
Wget:
```
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash
```
一旦安裝完成，重啟終端機並執行下列指令以安裝 Node.js。
```
nvm install stable
```
### 安裝Git
安裝Git的最佳方式是透過[Homebrew](https://mxcl.github.com/homebrew/)安裝。
```

title: Hexo 快速入门
date: 2015-10-14 23:09:52
tags:
---
## 1. 安装

前提是必须先安装 Node.js，至于怎么安装自己 Google 吧
```
npm install hexo -g
```
仅需一步就把 Hexo 本体和所有相依套件安装完毕，很简单吧？

## 2. 升级

更新hexo到最新版
```
 npm update hexo -g
```
## 3. 初始化

```
hexo init <folder>
```
如果指定 <folder>，便会在目前的资料夹建立一个名为 <folder> 的新资料夹；否则会在目前资料夹初始化。
## 4. 创建新博客
```
hexo new "Hello World"
```
## 5. 生成网站
```
hexo generate
```
## 6. 服务器
```
hexo server
```
伺服器会跑在 http://localhost:port （port 预设为 4000，可在 _config.yml 设定），也可以搭配 Pow 使用：
```
cd ~/.pow
ln -s /path/to/myapp
```
基本使用差不多就是这样子，非常简单。

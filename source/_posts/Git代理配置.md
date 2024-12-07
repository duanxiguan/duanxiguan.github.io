---
uuid: 7ce4d813-99fb-cdde-33fb-affa47d6869e
title: Git代理配置
date: 2024-11-03 18:10:10
author: 段希冠
categories:
- 后端
tags:
- Git

---
## Git代理配置

### 设置 Git全局代理
 
git config --global http.proxy 'http://127.0.0.1:2334'
 
git config --global https.proxy 'http://127.0.0.1:2334'
 
git config --global http.https://github.com.proxy 'http://127.0.0.1:2334'

git config --global https.https://github.com.proxy 'http://127.0.0.1:2334'

或者

git config --global http.proxy 'socks5://127.0.0.1:2334'

git config --global https.proxy 'socks5://127.0.0.1:2334'

### 查看 Git全局代理 配置
git config --global http.proxy

git config --global https.proxy

### 取消 Git全局代理
git config --global --unset http.proxy

git config --global --unset https.proxy

### 设置 当前项目Git代理
git config --local http.proxy '127.0.0.1:2334'

git config --local https.proxy '127.0.0.1:2334'
### 查看 当前项目Git代理 配置
git config --local http.proxy

git config --local https.proxy

### 取消 当前项目Git代理
git config --local --unset http.proxy

git config --local --unset https.proxy


 
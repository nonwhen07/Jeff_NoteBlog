---
title: Hexo筆記
date: 2024-06-04 14:21:14
tags: Hexo
---

## 環境安裝

- [Hexo 官網](https://hexo.io/zh-tw/)
- [Node.js 官網](https://nodejs.org/en)
- [Git 官網](https://git-scm.com/)

```
node -v
npm -v
git -v

npm install -g hexo-cli

hexo -v 
```

## hexo 指令
1. 建立部落格：`hexo init 你的網站名稱 `
3. 開啟伺服器：`hexo server`
4. 新增一篇部落格：`hexo new "部落格標題"`
5. 輸出實際網頁： `hexo generate`
6. 清除快取：`hexo clean`
7. 部署網站：`hexo deploy`

## 安裝 theme 內建樣版
* [安裝網址](https://github.com/hexojs/hexo-theme-landscape)

```
git clone --depth 1 https://github.com/hexojs/hexo-theme-landscape themes/landscape
```

## hexo 架構

```

- theme
 -landscape
  - config.yml 主題 config

- config.yml 全站設定

```
---
title: Vite筆記
date: 2024-06-04 14:20:10
tags: Vite
---

## VScode npm推薦安裝:

### vite安裝(Vite 官方網站：https://vitejs.dev/)
先在cmd確認npm版本(npm -v)、node版本(node -v)，接著照指示點選、npm install。
npm create vite@latest

```
npm create vite@latest
```

### bootstrap、bootstrap-icons

```
npm install bootstrap

npm i bootstrap-icons
```

### VeeValidate(標單驗證元件、18國語系)

```
npm i vee-validate --save

npm install @vee-validate/i18n
```

### vue-loading-overlay(方便的loading顯示工具)

```
npm install vue-loading-overlay@^6.0
```

### mitt(跨元件構通，可用於吐司邊傳訊息)

```
npm install mitt
```

### gh-pages套件:

vite 要部屬到sever上打包 => npm run build => 打包後出現dist資料夾用這包部屬

可參考https://ithelp.ithome.com.tw/articles/10202305

複製這條命令"deploy": "vite build && gh-pages -d dist"放在package,json的scripts欄位

```
npm install gh-pages

部屬指令:
npm run deploy
```
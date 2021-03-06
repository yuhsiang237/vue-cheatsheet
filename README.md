# vue-cheatsheet

在此紀錄Vue常用的元件、用法整理，方便需要時參考使用。  
這份比較偏向實際應用型，如果是基礎可以參考[Learn-Vue](https://github.com/unromanticman/Learn-Vue)這篇。

**附註：此份專案使用官方提供Vue CLI產生**

展示網站連結 https://yuhsiang237.github.io/vue-cheatsheet

已追加內容：
1.  多頁面路由vue router配置
2.  Vuex 狀態管理配置 
3.  IE11 支援配置
4.  常見生命週期函式
5.  父元件子元件溝通範例
6.  API串接範例
7.  頁面特效
8.  驗證錯誤用提示元件
9.  BootstrapVue Table元件使用範例
10. SCSS編譯&Bootstrap配置
11. 路由追蹤(未找到頁面匹配導向404頁面)
12. 巢狀路由範例

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### git pages
```
npm run build
cd dist 
git init 
git add -A
git commit -m 'deploy'
git push -f https://github.com/unromanticman/vue-cheatsheet.git master:gh-pages
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

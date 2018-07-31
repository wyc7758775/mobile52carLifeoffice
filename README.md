# m52carlifeoffice

> 卡莱官网移动端的网页

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```
## 整体架构
由于赶时间，大致是这样的
* 页面内容的渲染采用Vue.js
* ajax用vue-resource
* 页面样式用css和css3以及element-ui
* 轮播图暂时采用swiper.js
# my-project

> A Vue.js project

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

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).  

# About development process
## init Project 
```bash 
# 全局安装 vue-cli
$ npm install --global vue-cli
# 创建一个基于 webpack 模板的新项目
$ vue init webpack my-project
# 安装依赖，走你
$ cd my-project
$ npm install
$ npm run dev
```

## [API ](https://cn.vuejs.org/v2/guide/index.html)  


## compile lib   
```bash
# vuex
npm install --save vuex
# vue-router
npm install vue-router --save
```  

## Use [Vue-Router](https://router.vuejs.org/zh-cn/installation.html)    
```javascript
// main.js
// 导入VueRouter
import VueRouter from 'vue-router'  
// 安装路由功能
Vue.use(VueRouter)
let router = new VueRouter({
    mode: 'history',
    routes: [
        {
            path: '/',
            component: IndexPage
        }
    ]
})
new Vue({
  router,
})

// layout.vue
<keep-alive>
    <router-view></router-view> 
</keep-alive>

```　

## Use [Vuex](https://vuex.vuejs.org/zh-cn/) 

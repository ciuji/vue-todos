# my-todos

## intro
learn Vue from [liangxiaojuan/vue-todos](https://github.com/liangxiaojuan/vue-todos) and [学习不一样的vue](http://yangyi1024.com/2017/05/27/%E5%92%8C%E6%88%91%E4%B8%80%E8%B5%B7%E5%AD%A6vue%E5%90%A7/)

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

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


## tips
solve `Elements in iteration expect to have 'v-bind:key' directives.`

> If your component or element has no keys, you can do this:<br>
> `<p v-for='(person, index) in people' :key='index'> </p>`

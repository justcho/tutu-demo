# 突突 - 一个 VUE UI组件

[![Build Status](https://travis-ci.org/justcho/tutu-demo.svg?branch=master)](https://travis-ci.org/justcho/tutu-demo)

## 介绍

这是我在学习Vue过程中做的一个 UI 框架，希望对你有用

## 开始使用
1.添加CSS 样式

 使用本框架前，请在CSS中开启 border-box

 ```
 *,*::before,*::after{box-sizing:border-box;}

 ```
 IE 8 及以上浏览器都支持此样式。

 你还需要设置默认颜色等变量（后续会改为 SCSS变量）
 ```
   html {
            --button-height: 32px;
            --font-size: 14px;
            --button-bg: white;
            --button-active-bg: #eee;
            --bordor-radius: 4px;
            --color: #333;
            --border-color: #999;
            --border-color-hover: #666;
        }
 ```
 IE 15 及以上浏览器都支持此样式。
 
2.安装 tutu
```
npm i  --save justcho-tutu
```

3.引入 tutu
 ```
 import {Button,ButtonGroup,Icon} from 'justcho-tutu'
 import 'justcho-tutu/dist/index.css'
 export default {
   name: 'App',
   components: {
    'g-button':Button,
    'g-icon':Icon
   }
 }
 ```



## 文档

## 提问

## 变更记录

## 联系方式

## 贡献代码


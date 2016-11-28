# 概述

Web应用，俗称网站，随着网络技术的进步逐渐变得越来越多，功能越来越强大，受众面越来越广。那么一个Web应用是如何被开发出来的呢？

随着Web开发技术日新月异，如果你在2017年第一次接触Web开发，就会发现扑面而来的是各种各样的技术和框架，也许有如下疑问充斥着你的脑海:

1. 学什么？
2. 怎么学？
3. 这些框架是如何组合成一个应用的？
4. 先学习好JavaScript还是先学习好一个框架做出东西？
5. 我现在懂一些简单的HTML，CSS和JS了，然后呢？

本书的初衷就是从一个Web开发自学者的角度来为这些问题给出一个方案。

## 本书面向的人群

- 想要开始自学Web开发的学习者
- 想要了解Web应用构成的爱好者
- 苦于无法提高的入门Web开发者
- 想要了解一定后端的前端开发者

## 会讲什么

- 围绕一个简单的Todo List的Node应用展开讲解，随着对它进行功能扩展而探索Web开发从前端到后端的方方面面。
- 尽可能不使用框架（只用了Babel转码器和测试框架Mocha），用原生的方式对应用进行开发，让读者了解框架存在的意义。

## 不会讲什么

- 实现的语法，ES5和ES2016的区别。
- 语言的具体细节，例如用函数声明和函数表达式声明函数的具体区别。
- 语言api的实现原理，例如Node.js的各种模块。
- 不同操作系统上带来的差异。

## 目录

- 序
- 第1章：Web应用的基本架构
    - 我们看到的是什么
    - 何谓前后端
    - 动静有别
- 第2章：静态页面的构成
    - HTML
    - CSS
    - JavaScript
- 第3章：成为可访问的页面
    - 一个HTTP请求的旅行
    - 一个HTTP请求的组成
- 第4章：数据持久化
    - 数据存放在哪里
    - 关系型数据库
    - noSQL
    - 用mongoose存储你的数据
- 第5章：可重用的代码
    - NPM
    - 用模块化管理你的应用
    - 异常处理
    - 你一定需要单元测试
- 第6章：携带数据的HTML
    - 为什么需要模版引擎
    - 前端渲染和后端渲染
    - 打造一个模版引擎
- 第7章：前后端通信与状态保持方案
    - XMLHttpRequest
    - 异步方案进化史
    - REST风格的路由
    - Cookie
    - Session
    - LocalStorage
- 第8章：数据安全与加密策略
    - 不安全的数据传输
    - 加密与解密
    - 拖库和撞库
    - 让攻击者死在破解的路上
- 第9章：了不起的UI
    - CSS预处理
    - 浏览器动画进化史
    - 流畅的单页面应用
    - 响应式
- 第10章：数据为核心的前端架构
    - 讨厌的数据更新
    - 厉害的MVVM
    - 优雅的单向数据流
    - 虚拟Dom
- 第11章：前后端持续同步策略
    - 轮询
    - 长轮询
    - WebSocket
- 第12章：站在巨人的肩膀上
    - 我们解决过的问题
    - 框架是如何更优雅的解决的
    - 昨日重现
- 跋
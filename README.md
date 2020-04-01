---
description: 挑战Hard模式下的前端面试之旅
---

# 前端内参

## 版权许可

![](.gitbook/assets/image%20%2822%29.png)

本作品采用[知识共享署名-非商业性使用 4.0 国际许可协议](http://creativecommons.org/licenses/by-nc/4.0/)进行许可，只要保持原作者署名和非商用，您可以自由地阅读、分享、修改本书。

## 前言

如何在Hard模式下通过一线互联网公司的面试？

我，38岁的old程序员，2003年出版个人第一本互联网技术书籍，后来加入奇虎360和百度这两家一线互联网公司，从事前端与手机客户端技术性工作，并主持研发了亿级用户的手机APP。

![2017&#x5E74;&#x5728;&#x6DF1;&#x5733;](.gitbook/assets/image%20%2823%29.png)

2020年开年的一次新冠疫情，导致公司彻底倒闭，我也失业了（哎呀，人算不如天算）。现在，和很多程序员朋友一样有了新的挑战：重新找一份工作。我计划入职一线互联网公司做感兴趣的前端\(Front-End\)工作。因为年龄大，嗯，其实这是很难的，很多互联网公司的雇主似乎不太接受这样的，面试之旅已然进入Hard模式。面对如此逆境，我决定勤学苦练，用扎实的技术功底和优秀的面试表现打动雇主以达成目标。

在我复习/学习期间，查阅了国外和国内大量的一手文档资料，发现原始的资料相对少，即使有原始的资料也是论文式的，对英语阅读能力有非常大的挑战。而国内的资料大多数有错漏、不完整：首先是翻译问题非常大，术语翻译错误、译文表意模棱两可、原文内容翻译不完整，让人看了更加迷惑不解；国内网上的文章，绝大多数缺乏系统化论述，知识点分散零碎，而且有很多代码错误……各种原因，对自己的学习过程中造成了不少困扰。感同身后之后，因此整理、编写了本书（嗯，目前还正在写，许多章节等我们去“点亮”😸），把前端知识和前端面试要点梳理一遍，作为自己前端求职的复习/进阶内参。现在分享出来，每章开头用心地以写上本章导读，方便阅读前参考。

同时，我会假设你已经有了差不多3年的前端工作经验，这样你阅读本书的时候体验会更加愉悦。

如果我能通过自身努力最终能达成入职一线互联网公司的目标，那么更年轻、更健康和更聪明的你们只会做的更好。加油吧，弟弟妹妹们！

欢迎给我[@提建议](https://github.com/coffe1891/FERD/issues/new)，[@Twitter](https://twitter.com/coffe1891)记录了面试实时动态。

## 零、搞定Hard模式下的面试

1. 一线互联网公司面试前的准备
   * [一线互联网公司有什么不同？](0/0.1.1.md)
   * [该公司是做什么的，实力、前景、口碑怎样？](0/0.1.2.md)
   * 该岗位负责做什么的，岗位所属部门在什么位置，上升空间多大？
   * 反复打磨你的简历，然后投出去！
   * 面试官可能问到哪些笔试、面试题？
   * 如何在面试前就给人留下深刻印象？
   * 面试应该怎样穿着打扮？
   * 不要迟到！不要迟到！不要迟到！
   * [不卑不亢、不疾不徐地说话](0/0.2.2.md)
   * [当面试官问你“有什么问题要问我吗”，如何应对？](0/0.2.9.md)

## 壹、前端之灵：JavaScript/ECMAScript

1. 你需要知道的新东西 
   * [新版 ECMAScript 特性分析](1/1.1.1.md)
   * JavaScript未来性能优化的方向
2. 核心概念
   * [函数](1/1.2.1.md)
   * [作用域、执行上下文、作用域链](1/1.2.2.md)
   * [彻底搞懂 this](1/1.2.3.md)
   * [深入理解 call、apply、bind ](1/1.2.4.md)
   * [面试时高频问到的“闭包” ](1/1.2.5.md)
   * [原型和原型链](1/1.2.6.md)
   * [同步和异步，阻塞和非阻塞](1/1.2.7.md)
   * [Event loop](1/1.2.8.md)
   * [强大的数组](1/1.2.9.md)
   * [正则表达式](1/1.2.10.md)
   * rest和spread操作符
   * 异步迭代和Promise.prototype.finally
   * [模块化开发](1/1.2.13.md)
3. 容易被问到的知识点
   * 深拷贝与浅拷贝
   * JavaScript函数柯里化
   * 用 Reduce 实现 Promise 串行执行
   * Proxy的各种用法
   * 用JavaScript实现类、继承
4. 浏览器、V8引擎
   * 网页被浏览器绘出来过程是怎样的？
   * 页面重排（Reflow）与重绘（Repaint\) 
   * DOM、Shadow DOM、Virtual DOM
   * V8引擎是如何工作的
   * V8引擎内存管理和垃圾回收机制
5. 相关的后端知识点
   * 为什么要创造服务器端的javascript—Node.js？
   * 了解TCP/IP、UDP、TLS 
   * Http协议的三个版本
   * Http和Https的区别在哪里
   * XSS与CSRF
6. 书籍推荐
   * 面试官问你读过哪些Javscript书籍

## 贰、[数据结构与算法](2/2.0.md)

1. 面试时高频率出现的算法
   * [十大经典排序算法](https://www.runoob.com/w3cnote/ten-sorting-algorithm.html)
   * [单调栈](https://blog.csdn.net/lucky52529/article/details/89155694)
   * 二叉树的遍历
   * 二叉树中的最大路径和
   * [实战：字节跳动前端面试2道算法题](2/2.1.4.md)
   * 实战：滴滴打车面试算法题
2. 其他算法理论
   * [面试官问你斐波那契数列的时候不要太高兴](https://zhuanlan.zhihu.com/p/54378423)
   * 尾递归究竟是好是坏
3. 好书推荐
   * [《学习JavaScript数据结构与算法》](https://book.douban.com/subject/27129352/)

## 叁、主流框架

1. 综合比较
   * jQuery相对现在流行的库而言过时了吗？
   * 开发跨平台app推荐React Native还是flutter？
   * Angular和Vue.js深度对比
2. Vue.js
   * 问得最多的Vue.js面试题 
   * Vue.js源码解读：Vue数据响应式原理
3. Angular.js
   * 你真的懂Angular.js吗？
   * Angular.js性能优化要点
4. React
   * 面试官高频问到的一些实现原理
   * React的性能优化技巧
5. flutter
   * flutter开发初体验
6. 好书推荐
   * [《深入浅出Vue.js》](https://book.douban.com/subject/32581281/)
   * [《深入React技术栈》](https://book.douban.com/subject/26918038/) 

## 肆、动效

1. 动效应用的场景
   * 不要拒绝设计小姐姐的要求  
   * 有效的引导用户
   * 让页面拥有生命力
2. css3动画基础 
   * transition过渡 
   * animation动画 
3. css3动画实践 
   * 弹窗  
   * 逐帧动画  
   * 悬浮按钮  
   * 广告动画  
   * 3D动画  
4. canvas 
   * 画布的基本功能
   * 分享到朋友圈的预览图制作
   * 飞机大战小游戏     
5. webgl
   * 3d的基础知识
   * 谁都会做的全景图  
   * 3d跑酷小游戏  

## 伍、必会的工具

1. Webpack-自动打包模块工具
   * 深入理解Webpack打包
   * 常用的脚手架 
2. API文档管理
   * 用Swagger解决API文档更新的烦恼
3. IDE-工欲善其事必先利其器
   * 高效使用VSCode的10点建议
   * 适用于前端开发者的20个VSCode插件
   * Sublime Text

## 陆、设计原则与编程范式

1. 设计原则——先有美的设计，才有美的实现
   * 单一职责
   * 最少知识
   * 开放-封闭
   * 面向接口编程
   * 代码重构
2. 面向对象编程（OOP）
   * 「面向对象」和「面向过程」有什么区别？
   * 面向对象编程的弊端是什么？
   * 重新认识JavaScript面向对象: 从ES5到ES6 
3. 函数式编程
   * 什么是函数式编程思维？
4. 响应式编程
   * RxJS
5. 元编程
   * Javascript元编程
6. 好书推荐
   * [《重构》](https://book.douban.com/subject/4262627/)

## 柒、掌握常见的设计模式

1. 面试时很容易聊到的十四种经典设计模式
   * 单例模式
   * 策略模式
   * 代理模式
   * 迭代器模式
   * 发布-订阅模式
   * 命令模式
   * 组合模式
   * 模板方法模式
   * 享元模式
   * 职责链模式
   * 中介者模式
   * 装饰者模式
   * 状态模式
   * 适配器模式
2. MVVM、MVC、MVP
   * 聊点不一样的MVVM 
   * 有了MVC为什么还要MVVM？
   * MVP又是什么？

## 捌、参考网站

1. [中文站-Mozilla大宝库](https://developer.mozilla.org/zh-CN/docs/Web) 最全的Web相关参考文档,没有之一
2. [英文站-StackOverflow](https://stackoverflow.com/) 掌握了四级英语就能向老外提问交流了,解决疑难杂症必上
3. [中文站-Vue.js手册](https://www.w3cschool.cn/aekdgs/) 手册在手,玩转Vue不愁
4. [中英文-Vue资源大全](https://github.com/vuejs/awesome-vue) 超级多的资源,总能找到你喜欢的那款

## 玖、公众号&博客推荐

1. 公众号
   * 奇虎360 
   * 阿里巴巴
   * 腾讯
   * 字节跳动
   * 百度
   * 其他：网易、滴滴、快手、京东……
2. 博客
   * 每一个前端工程师都应该关注的博客

## 拾、后记

1. 讨论、纠错、更新，本书源代码下载
2. 前端展望：百川奔流直入海


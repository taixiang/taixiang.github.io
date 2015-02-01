---
layout: post
title: '如何布局并管理好项目目录（1/2）'
categories:
    - 规范和标准
tags:
    - 项目管理
    - 翻译
---

![Figure](http://blog-fungenomics-com.qiniudn.com/st.post.2015-01-13-Fig1-1.png)

不同类型的项目会有适合其特点的目录布局，很难说会有一个真正的标准，我这里特指的是基因组（或相关的）项目目录布局问题。

基因组项目目录结构的科学管理是一个非常重要的问题。如果不科学，东西一多更是成了灾难，很多时候你想找的东西并不是丢了，而是根本找不到了！有时更糟的是就算找到了，也会忘了是怎么来的，最后连自己都会怀疑它是不是真的就是正确的那一份！只得一轮又一轮地冥思苦想寻找着若隐若现的线索，甚至有时即使打算重做都不知道该怎么下手，效率真是极低，简直就是在浪费生命！这样下去根本没得玩，直到昨天我才意识到实际上要用程序设计的思想来管理每个项目的目录！还是[A workflow for R](http://blog.revolutionanalytics.com/2010/10/a-workflow-for-r.html)这篇博文给我的灵感，它提出了一些规则：

* __透明__（Transparency）：目录布局清晰明朗，逻辑清楚，整个结构一看就能明白。    
* __易维护__（Maintainability）：容易实行项目的修改和相关（如文件名、目录变换）调整。           
* __模块化__（Modularity）：任务之间都应该尽可能保持其独立性，每一个就只干好自己的事，不干涉其他任务，避免牵一发而动全身的情况发生，要有一一对应的关系，这样即便是需要修改也将会非常方便。     
* __可移植__（Portability）：项目可以很容易地移植到其他的平台或者系统中。     
* __易复现__（Reproducibility）：不论经过多久，都要能轻易重现原来的结果。     
* __秒懂__ (Efficiency)：无需多想就能明白项目执行过程中的相关细节，比如所要解决的每个问题是如何处理的和所用的工具是什么等等。

这几点完全说出了项目布局和目录管理所应达到的目的和状态，值得铭记于心多拿来参考参考。只是仅有理论，还是太过不着边际了点，有必要弄个例子来看看具体应该怎么做。

...[未完待续]()



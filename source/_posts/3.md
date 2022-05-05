---
title: Redstone_Calculator
author: 凛梦
date: 2020-03-17 09:01:31
tags:
 - Game
 - Minecraft
 - 红石
categories:
 - Game
---

### 什么？你还不会小学数学？让红石计算器来帮你吧！  
---
## 前言&~~废话~~
  
**数电真心不容易，我现在体会到挂科的痛苦了orz**  

**布线时序一生之敌**  
  
先放一张预览图  

![6.jpg](https://i.loli.net/2020/03/17/C7qrsfSvacpeODH.jpg)  

<!--more-->
  
**计算器可以计算加法，清零两个功能**  
  
~~没有剩余的三则运算是因为不想堆模块<span style="background:#403E3E;">就是懒</span>~~

---

## 模块介绍
 - 键盘为DEC输入转BCD输出，输出为4bit
 - 双向移位寄存器，由于退位有bug故没有做退位的时序
 - BCD全加器
 - 两个16Bit内存来存储加数
 - 纯红石显示屏
 - 前导零消除器  

**然后来一张侧面图**

![侧面2.jpg](https://i.loli.net/2020/03/17/IZ9il4QSgDpAVFO.jpg)

---

### 显示屏模块

显示屏用的依旧是上次的设计，堆叠三层之后我知道字库和压缩布线的重要性了  (哭  
 - [上次的显示屏链接](https://mengyan233.top/2020/03/10/%E7%BA%A2%E7%9F%B3%E7%A7%BB%E4%BD%8D%E6%98%BE%E7%A4%BA%E5%B1%8F_Alpha_0.0.2/)  

比较有意思的是我在布线过程中自己做了一种可以水平和垂直互不干扰的布线方法

![3.jpg](https://i.loli.net/2020/03/17/HJibqcLjyMxW6Ag.jpg)

---

### 计算模块

计算模块只不过由一个BCD全加器构成

**BCD全加器**的原理是在全加器的基础上多出了满十加六模块，具体可以参考这篇文章

 - [BCD码的加法和减法](https://blog.csdn.net/leelitian3/article/details/83903865)

所以BCD全加器就是在普通全加器的基础上做**满十加六**  
  
其他部分就没有什么亮点了

### 输入模块

输入模块在这里不想用按钮输入，于是使用了高逼格的键盘代替空洞的按钮 ~~<span style="background:#403E3E;">我知道布线惨不忍睹</span>~~  
  
![键盘.jpg](https://i.loli.net/2020/03/17/dTZ79ukCGvmM4LI.jpg)

---

**✿✿ヽ(ﾟ▽ﾟ)ノ✿完结撒花！**    
  
  
  
  
什么你还想要存档？？

行吧给你把  
  
[蓝奏云盘](http://t.cn/A6zOzEFN)  
  
推荐的游玩版本是电脑Java版1.15.2哦
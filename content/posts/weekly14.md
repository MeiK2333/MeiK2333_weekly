---
title: 每周分享第 14 期
date: 2019-02-21 15:47:38
tags:
---

记录我过去一周看到的值得分享的东西，每周四发布。

<small style="color: #33333333">过年拖更不是常识么？（连阮一峰老师都停更了一期）</small>

这期短是短了点，不要嫌弃，下周我一定补上。

<!--more-->

## 随笔

### 猪年快乐

![](/weekly14/9265.jpg_wh1200.jpg)

不知不觉一年过去了啊，我还是依旧如此菜鸡……过去一年发生了不少事，幸好大多是好事……

刚过阳历一月一日的时候还不习惯，写时间还是习惯 2018 起手。等到农历年过了才有了实感，才真真切切的感觉到新的一年来到了。

要说新年我有啥新气象的话，那就是我划水更加熟练了……

（听说为了 msl 的避讳，今年特意淡化了猪的元素，不知道是真的假的……）

### Chrome ctrl + enter 补全 .com

你可以在 Chrome 的地址栏中输入 `meik2333`，然后按 `Ctrl + Enter`。

### [在试图改变这个世界的时候，请保留一份敬畏](https://blog.csdn.net/Emptyset110/article/details/49879413)

一行代码不写，把自己加到作者名单里，和 copy 了别人的代码，但是只把 `LICENSE` 删除，两个可能半斤八两吧。

### [PawSense](http://www.bitboost.com/pawsense/)

这是一个跨时代的软件：它可以检测到你的猫在踩你的键盘，并且忽略掉你的猫想打出的字（对猫来说，这不公平）。

### [【曝光】一个无耻的程序员可以多无耻？](https://www.abbeyok.com/archives/316)

相关事件在 V 站上的讨论帖是我见过唯一一个能三天置顶的贴……我有幸见证了全过程。

一开始有人[发帖质疑](https://www.v2ex.com/t/534800) @88250 的论坛“黑客派”在使用 GitHub 登录时会申请额外的权限，比如库的写权限、修改邮箱的权限等，并滥用这些权限擅自 star 88250、follow 它的项目。热心网友很快发掘出了这个人之前的劣迹。88250 假意道歉，然后回到自己的论坛开骂。这种行为很快被 V 站网友发现，双方又掀起一波怼战。

反正过程有意思极了，可以看看这篇博客的记录。我反正是仔细检查了一遍我的 Github Application，确定没有什么山寨第三方获得了我的权限。

## 技术杂谈

### [使用SSH反向隧道进行内网穿透](http://arondight.me/2016/02/17/%E4%BD%BF%E7%94%A8SSH%E5%8F%8D%E5%90%91%E9%9A%A7%E9%81%93%E8%BF%9B%E8%A1%8C%E5%86%85%E7%BD%91%E7%A9%BF%E9%80%8F/)

有些时候我们需要穿透到内网中进行某些操作，或者使用云服务器穿透到家庭的局域网中进行操作。

这篇文章介绍了使用 ssh 进行（正向与反向）内网穿透的方法。

### [Chrome DevTool Overrides](https://developers.google.com/web/updates/2018/01/devtools)

Chrome 的这个新功能可以让前端远程调试网站的样式与 JS。首先将一个本地文件夹与远程网站建立映射，然后在 `DevTools - Sources` 中修改样式或 JS，`Ctrl + S` 可以将修改后的文件保存到本地，然后刷新页面， Chrome 会忽略远程网站的这些文件，自动从本地加载文件。

其实不仅只有前端可以使用，写爬虫的时候这个工具也是很有用的。可以通过修改网站的 JS 来让破解目标网站变得轻松一些。

### [Proton](https://github.com/ValveSoftware/Proton)

Steam 基于 wine 开发的软件，可以在 Linux 环境下运行部分 Windows 的游戏。官方名单里有诸如《尼尔机械纪元》这类大作。

我试了一下，除了几个小黄油不支持外，我的大部分游戏都可以通过 Proton 直接执行，而且并没有感觉到额外的卡顿。

### Recent Contests

- [浏览器插件](https://github.com/dreamerblue/recent_contests)
- [数据源](https://github.com/MeiK2333/recent_contests)

这是一个让 OI/ACM 选手能便捷的看到最近的比赛的插件（虽然还没有完全完成）。

### [螺旋式读取 C 的变量类型](http://c-faq.com/decl/spiral.anderson.html)

这篇文章教你如何去读 C 的变量类型。

CPPPP 里曾经介绍过一种类型：`指向函数指针数组的数组指针的指针`。它的变量类型声明是这样子的：`const double * (* (* pd)[3])(const double *, int) = nullptr`。

## 音乐分享

今天没有表情包，就送大家十个版本的届不到吧。

顺带一提，我最喜欢的是学姐（茅野愛衣）版。

### 届かない恋-茅野愛衣

<audio src="/weekly14/届かない恋-茅野愛衣-002BbUoO2fU5cV.m4a" controls="controls">
Your browser does not support the audio tag.
</audio>

### 届かない恋-上原れな（原唱版本）

<audio src="/weekly14/届かない恋-上原れな-0044XSxC3rZYir.m4a" controls="controls">
Your browser does not support the audio tag.
</audio>

### 届かない恋-米澤円

<audio src="/weekly14/届かない恋-米澤円-002vFrhZ4eRX87.m4a" controls="controls">
Your browser does not support the audio tag.
</audio>

### 届かない恋-上原れな

<audio src="/weekly14/届かない恋-上原れな-001SU5cn0qwt7h.m4a" controls="controls">
Your browser does not support the audio tag.
</audio>

### 届かない恋 ~It Disappeared in Flakes~-天游

<audio src="/weekly14/届かない恋-天游-002vQMH31dNjZv.m4a" controls="controls">
Your browser does not support the audio tag.
</audio>

### 届かない恋-Kana

<audio src="/weekly14/届かない恋-Kana-003Yb0OO3BNSMM.m4a" controls="controls">
Your browser does not support the audio tag.
</audio>

### 届かない恋-羽吹梨里

<audio src="/weekly14/届かない恋-羽吹梨里-001kYLVs3wQUTs.m4a" controls="controls">
Your browser does not support the audio tag.
</audio>

### 届かない恋-米澤円

<audio src="/weekly14/届かない恋-米澤円-002lNveO34R3ET.m4a" controls="controls">
Your browser does not support the audio tag.
</audio>

### 届かない恋-生天目仁美

<audio src="/weekly14/届かない恋-生天目仁美-000Xk0xw0bmlu4.m4a" controls="controls">
Your browser does not support the audio tag.
</audio>

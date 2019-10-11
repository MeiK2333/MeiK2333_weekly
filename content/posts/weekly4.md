---
title: 每周分享第 4 期
date: 2018-11-08 12:17:16
tags:
---

记录我过去一周看到的值得分享的东西，每周四发布。

<!--more-->

## 随笔

### Gmail 的神奇用法

#### 加号的用法

![](/weekly4/gmail.png)

![](/weekly4/gmail1.png)

![](/weekly4/gmail2.png)

Gmail 会忽略用户名中 `+` 后面的部分，因此以上几封邮件都是发给 meik2333@gmail.com 这个邮箱的。

#### 点号的用法

![](/weekly4/gmail3.png)

Gmail 会忽略用户名中的 `.`，因此这封邮件的实际收件人还是 meik2333@gmail.com。

QQ Mail 也支持这个特性。

#### gmail 与 googlemail

meik2333@gmail.com 与 meik2333@googlemail.com 对应同一个邮箱。

![](/weekly4/googlemail.png)

### Google Analytics

Google Analytics 表示，周二那天我的网站的访问量同比增长 400%。

![](/weekly4/analytics.png)

这是我两个网站（meik2333.com 和 weekly.meik2333.com）的总和，写了博客没人看其实是挺让人难受的......

### [Blog](https://github.com/MeiK2333/blog)

我计划开发一个静态资源服务器，下面是预计包含的功能：

- 静态资源解析
- 302 缓存
- Range
- Keep-Alive 支持
- 反向代理
- HEAD、OPTION
- HTTPS 支持
- ......

其实我之前已经写了一个版本了，但我在写那个的时候又有了很多新的想法，因此就决定重新写个新的。

## 新闻

### [重庆万州公交车坠江原因公布：乘客与司机激烈争执互殴致车辆失控](http://cq.people.com.cn/n2/2018/1102/c365401-32235920.html)

关于此事，很多网友评论称遇到此类事件一定要果断出手。

可是从乘客开始攻击司机到公交车撞栏杆只有短短 3 秒，除非是在乘客刚开始与司机争吵的时候就阻止二人，否则悲剧还是很难避免。

### 蓝洁瑛去世

![](/weekly4/30娘.jpeg)

### Chinses bots

恭喜中国歌迷成功将 **Chinese bots** 刷上了 Twitter 北美热搜。

![](/weekly4/chinese-bots.png)

（Chinese bots 译为中文是“水军”的意思。）

另外，这位歌手曾荣获 2017 年 **8th Golden Broom Awards** 的 **Most Disappointing Actor** 奖项。

![](/weekly4/most-disappointing-actor.png)

## 技术杂谈

### [How-To-Ask-Questions-The-Smart-Way](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way)

本文原文由知名 Hacker Eric S. Raymond 所撰寫，教你如何正確的提出技術問題並獲得你滿意的答案。

我个人奉为圣经的一篇文章，推荐每个人都看一下。

### [libseccomp](https://github.com/seccomp/libseccomp)

[seccomp](https://en.wikipedia.org/wiki/Seccomp) 是 Linux 2.6.12 新增的方法，用处是让进程拒绝除 `exit()`、`sigreturn()`、`read()` 和 `write()` 之外的所有系统调用。

seccomp-bpf 是 seccomp 的扩展，可以自定义过滤规则。Chrome 的沙箱就是基于 seccomp-bpf 开发的，Docker 也可以定义 seccomp 规则。

libseccomp 也可以自定义过滤规则，而且更加易用，可以用于开发沙盒系统（比如 Online Judge 的评测系统）。

在 Ubuntu 上可以这样安装它：

```bash
sudo apt update
sudo apt install libseccomp-dev
```

[这里](https://blog.yadutaf.fr/2014/05/29/introduction-to-seccomp-bpf-linux-syscall-filter/)是一个使用 libseccomp 的例子。

### [Python 编程之美](https://book.douban.com/subject/30314669/)

Kenneth Reitz 大神的书，我这周看了大半本。

正如书中所写，这本书并不适合用来 Python 入门，这本书面向的读者是已经有一定的 Python 基础、希望更上一层楼的。

如果你正好是这种人，那么选这本书绝对没错。

## 表情包

### 延迟

![](/weekly4/ping.jpg)

### 突然自闭

![](/weekly4/close.jpg)

### 双十一特惠

![](/weekly4/1111.jpg)

### 中国现在的追星日常

![](/weekly4/fans0.png)

![](/weekly4/fans1.png)

![](/weekly4/fans2.png)

![](/weekly4/fans3.png)

（虽然是反讽，但是很真实了。）

### K/DA - POP/STARS

让我们来看一下这个超越了 Kirs Who 的 K/DA 首单吧。

<video src="/weekly4/kda.mp4" controls="controls" width="100%">
Your browser does not support the audio tag.
</video>

K/DA 四人（？）有同一个特点，你们发现了吗？

没错，四个人大招都是位移！

按这个规律，K/DA 的下一位成员应该是...黛安娜？（貌似雷克塞也是女性来着）

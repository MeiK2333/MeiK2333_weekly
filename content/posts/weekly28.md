---
title: "每周分享第 28 期"
date: 2019-10-28T17:17:27+08:00
---

记录我过去一周看到的值得分享的东西，每周日发布。

<!--more-->

---

> 要说去看心理医生，多少会解决一些心理障碍吧，实际上满不是那么回事。心理医生听起来很了不起，其实都是些敷衍了事的家伙。他们煞有其事地听着我说话，就知道嗯嗯的点头，这个我也会啊。——《没有女人的男人们》 - 村上春树

---

## 随笔

### 提笔却无言

换了新的博客系统后，我迟迟没有更新每周分享。说起来我最近好像是挺忙的，但其实还是能抽出时间来写的。之所以近两个月没有更新，只是因为懒而已……

不过，新的博客系统比之前的确实好用了不少，我的博客里面有很多图片和视频音乐等资源，之前的 hexo 系统对这个处理极慢，每次生成页面要用几分钟。换了 hugo 之后，这个时间降低到了毫秒级别。

之前用 hexo 的时候，选了里面最简洁的一个主题。转到 hugo 之后，没有找到类似的主题，于是我干脆自己从 GitHub 的样式里扒了一套出来，感觉还挺好看的。

### [goodreads](https://www.goodreads.com/quotes/)

名人名言语句摘录。

## 新闻

### [谷歌量子计算机运算200秒=世界第一超算运算10000年](https://www.huxiu.com/article/318966.html?utm_source=tuicool&utm_medium=referral)

谷歌宣布，在一个精心挑选的问题上，量子计算机计算 200 秒可以得出结果，而目前世界排名第一的超算需要运算 10000 年。

虽然这个问题没有什么现实意义，但已经可以证明在某些情况下，量子计算机与传统的计算机的运算能力不在一个数量级上，未来可能会出现量子霸权。

## 技术分享

### [为什么是 Go 而不是 Rust](https://www.infoq.cn/article/Wz9FPaammsmGMO5NJXPx?utm_source=tuicool&utm_medium=referral)

> Google 创建 Go 语言是为了解决 Google 的问题，这些问题主要涉及网络服务。Go 的并发模型非常适合服务器端应用程序，这些应用程序必须主要处理多个独立请求，而不是参与复杂的结果传递方案。这就是为什么给你的是 go 而不是 wait 的原因之一。

作为最近很热门的两门语言，Go 和 Rust 经常被拿来进行比较，总体来说，有以下方面。

- Go 速度很快，但 Rust 速度更快。
- Go 有一个高效的垃圾收集器，但 Rust 有静态内存管理。
- Go 有很好的并发支持，但 Rust 有可证明的正确并发性。
- Go 有接口，但 Rust 有特性和其他零成本的抽象。
- Go 可以交叉编译到目标平台的二进制文件，Rust 也可以。
- Go 有优秀的并发模型（Goroutine），Rust 也有，而且额外有 `wait` 支持。
- Go 编译极快，Rust 在另一个极端上。
- Go 风格统一，通过 `go fmt` 转换为统一的格式，而 Rust 有太多的写法。
- Go 的学习成本很低，比起 Java 等语言来说，使用 Go 更难陷入令人难以理解的陷阱中；而与之对应的，就是 Rust 令人诟病的陡峭的学习曲线。

Go 简单易学，有良好的性能和并发支持；而 Rust 追求极致的性能与安全，这让它的学习成本很高。

用户可以根据自己的需求进行选择，只要记住这句话：Go 是更好的 Java，而 Rust 是更好的 C++。

### [DNS 安全](https://meik2333.com/posts/dns-security/)

域名系统 DNS (Domain Name System) 是互联网中最重要的协议之一，DNS 将域名转换为 IP 地址，以便浏览器加载互联网上的资源。

作为互联网的基石协议之一，原始的 DNS 协议却是非常脆弱的。基于 UDP 的明文传输使得 DNS 极易被攻击、被记录，以及被篡改。

### [github-style](https://github.com/MeiK2333/github-style)

一个 GitHub 风格的博客主题，我的博客就是这个主题。

### [Google Engineering Practices Documentation](https://github.com/google/eng-practices)

谷歌工程规范文档。

### [uber-go/guide](https://github.com/uber-go/guide/blob/master/style.md)

Uber 开源的 Go 语言编码风格指导。

### [build-your-own-x](https://github.com/danistefanovic/build-your-own-x)

建立自己的技术。

### [中文文案排版指北](https://github.com/sparanoid/chinese-copywriting-guidelines)

统一中文文案、排版的相关用法，降低团队成员之间的沟通成本，增强网站气质。

### [约定式提交](https://www.conventionalcommits.org/zh-cn/v1.0.0-beta.4/)

一种用以给提交信息增加人机可读的信息的规范

### [utterances](https://utteranc.es/)

为静态博客站点添加评论功能的程序，基于 GitHub Issues。

## 文摘

---

> 目前，最强大的优化工具恐怕就是 `delete` 键了

---

> 完美之道，不在于无可增加，而在无可删减

---

> “没有什么能像单恋一样使花生酱失去味道。”——查尔斯·舒尔茨（Charles M. Schulz）

---

## 表情包

### 单方面女友

<div style="text-align:center">
<img src="/weekly28/单方面女友.webp">
</div>

### 98 年大叔

<div style="text-align:center">
<img src="/weekly28/98年大叔.jpg">
</div>

### 程序员噩梦

<div style="text-align:center">
<img src="/weekly28/程序员噩梦.jpeg">
</div>

### 大长腿

<div style="text-align:center">
<img src="/weekly28/大长腿.webp">
</div>

### 蛋疼

<div style="text-align:center">
<img src="/weekly28/蛋疼.gif">
</div>

### 心疼

<div style="text-align:center">
<img src="/weekly28/心疼.gif">
</div>

### 肾疼

<div style="text-align:center">
<img src="/weekly28/肾疼.gif">
</div>

### 迷惑行为

<div style="text-align:center">
<img src="/weekly28/迷惑行为.gif">
</div>

### 看你XX

<div style="text-align:center">
<img src="/weekly28/看你妈B-1.jpg">
</div>
<div style="text-align:center">
<img src="/weekly28/看你妈B-2.jpg">
</div>

### 紫薇，紫薇！

<div style="text-align:center">
<img src="/weekly28/紫薇，紫薇！.gif">
</div>

### 敬礼

<div style="text-align:center">
<img src="/weekly28/敬礼.gif">
</div>

### 还是枪好用

<div style="text-align:center">
<img src="/weekly28/还是枪好用.gif">
</div>

### 当你 30 岁

<div style="text-align:center">
<img src="/weekly28/当你30岁1.jpg">
</div>
<div style="text-align:center">
<img src="/weekly28/当你30岁2.jpg">
</div>

### 干啥啥不行，吃饭第一名

<div style="text-align:center">
<img src="/weekly28/干啥啥不行，吃饭第一名.jpg">
</div>

### 就是他妈的扛不住哇

<div style="text-align:center">
<img src="/weekly28/就是他妈的扛不住哇.jpg">
</div>

### 喵

<div style="text-align:center">
<img src="/weekly28/喵.gif">
</div>

### 请你想想办法

<div style="text-align:center">
<img src="/weekly28/请你想想办法.jpg">
</div>

### 她爽快的答应啦

<div style="text-align:center">
<img src="/weekly28/她爽快的答应啦.png">
</div>

### 我超喜欢你

<div style="text-align:center">
<img src="/weekly28/我超喜欢你.jpg">
</div>

### 约会指南

<div style="text-align:center">
<img src="/weekly28/约会指南.png">
</div>

### 做你自己

<div style="text-align:center">
<img src="/weekly28/做你自己.jpg">
</div>

### 我的代码

<div style="text-align:center">
<img src="/weekly28/my-code.png">
</div>

## 音乐分享

### 野狼 Disco

<audio src="/weekly28/宝石Gem,陈伟霆-野狼Disco（feat.陈伟霆）.flac" controls="controls">
Your browser does not support the audio tag.
</audio>

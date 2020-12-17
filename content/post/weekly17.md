---
title: 每周分享第 17 期
date: 2019-03-21 15:42:31
tags:
---

记录我过去一周看到的值得分享的东西，每周四发布。

<!--more-->

## 随笔

### 小云服务商把我的服务器给重置了

前几天在一家小型的云服务商处买了一个 KVM 服务器，不知道哪里出了问题，CPU 占用率过高导致被关闭了。

经过交流之后，服务商同意重新给我开启服务，然后厉害的就来了：他把服务器重装了系统，然后把密码通过邮件发送给我了……

### 给你们看一个求锤得锤的典型案例

[《没错，我就是钉钉考勤的开发，不爽的冲我来》](https://www.v2ex.com/t/543481)。

不论技术，我认为开发钉钉的人价值观绝对是有问题的：钉一下、垃圾推送、无限多的红点、无底线的权限要求、无底线的隐私获取……

这样的公司，再多的工资我也不会去的。人生在世几十年，若被钉死在互联网乃至社会的耻辱柱上，死后仍有骂名，那真可谓是遗臭万年了。

### [B站贴吧的崩塌与重建：270万人在一夜之间彻底乱套](https://zhuanlan.zhihu.com/p/59566171)

贴吧版《权利的游戏》，RBQ，RBQ！TQL，WSL！

早些年贴吧的氛围还是很好的，当年（12-15年）我还在水 LOL周免吧，吧里除了每周都有的黑周免环节外，还有自己的视频制作组和高玩。Lin小北和纱布德都是从这里出来的，小北当年那期上过多玩年度视频的[五杀瑞文](http://lol.duowan.com/1412/282649922128.html)和回流身法 VN 都是在 LOL周免吧时期出的，早期视频里还有“LOL周免吧”的字样。

可惜小北和纱布德最终也没有非常火，纱布德已经消失好多年了，小北好像转吃鸡了。吧里例行的“黑周免”也开始懈怠了，直到后来完全停了。现在 LOL周免吧已经被广告占领了，最近的精品贴也停留在了 16 年 2 月。想来当年那批吧友应该也都工作甚至娶妻生子了吧，打开贴吧全是广告贴，一个旧人都看不到，怎能让人不触景生情呢。

当然，也存在一些遗世独立的贴吧，比如我已经靠签到水到九级的[神奇海螺吧](https://tieba.baidu.com/f?kw=%E7%A5%9E%E5%A5%87%E6%B5%B7%E8%9E%BA&fr=index)。

## 新闻

### [VS 绿帽子](https://developercommunity.visualstudio.com/content/problem/475341/vs-installer-welcome-image-contains-offensive-elem.html)

Visual Studio Installer 因为图片中的小人戴绿帽子而被报 BUG 了， V 站相关讨论[《如何评价 visual studio installer 因包含戴绿帽子的人的图片而被报 bug？》](https://www.v2ex.com/t/543962)。

我觉得还好，从原文来看，作者只是简单的描述了绿帽子在中国的特殊含义，并建议修改，并无不妥之处。

## 技术分享

### 服务器开启 bbr 后无法访问可以关闭防火墙来解决

bbr 是谷歌开源的拥塞控制算法，在现行的网络环境中比传统的拥塞控制算法有更好的体验。YouTube 已经上了 bbr 技术。

个人的服务器也可以开启 bbr 来提高网络 IO，但服务器开启 bbr 后有可能会无法访问，此时可以通过关闭防火墙来解决。

```bash
systemctl stop firewalld.service
systemctl disable firewalld.service
```

当然，这种方法虽然简单粗暴，但有很多安全隐患，没啥用的云服务也就算了，自己的服务器可不要这样搞……

### [cpulimit](https://github.com/opsengine/cpulimit)

cpulimit 是一个可以限制进程 CPU 使用率的工具，其原理是通过 POSIX 信号 SIGSTOP 和 SIGCONT 来控制进程状态。我通过 cpulimit 来确保我的 KVM 不会再因为 CPU 使用率过高而被关闭。

### 保留作为示例的 IPv4 地址

根据 [rfc5737](https://tools.ietf.org/html/rfc5737) 规定，有三个 IP （192.0.2.0/24、198.51.100.0/24 、203.0.113.0/24）被保留以用作文档与示例。

类似的有用作示例的网站：[example.com](http://example.com/)，以及用于测试 HTTP 请求的网站 [httpbin.org](http://httpbin.org/)。上手 `curl http://httpbin.org/get` 才是使用 `cUrl` 的正确方式:-D。

### I'm a teapot

rfc 不只有严谨的规定，还有很多有趣的东西，比如[这个](https://tools.ietf.org/html/rfc2324)。

你可以使用 `cUrl` 来看到这个茶壶：

```bash
curl http://httpbin.org/status/418
```

## 视频分享

表情包最近看来还要一直鸽了，不过我三月底就要离职回学校了，到时候就有时间收集表情包了。

### 她曾活过啊

<video src="/weekly17/她曾活过啊.mp4" controls="controls" width="100%">
Your browser does not support the audio tag.
</video>

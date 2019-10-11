---
title: 每周分享第 15 期
date: 2019-02-28 14:25:00
tags:
---

记录我过去一周看到的值得分享的东西，每周四发布。

<!--more-->

## 随笔

### 仿 GitHub 的博客风格: [小白妹妹写代码](https://sabrinaluo.github.io/tech/)

这周我看到了一个博客，风格高仿 GitHub，很有创意。

只是有个问题：它右上角那个消息提示的小蓝点点不掉，让强迫症颇为难受。

### 类库被你的代码调用，但框架主动调用你的代码。

在某篇博客中看到的一句话，作者提倡减少框架的依赖，转而使用类库。

### [已经 2019 年了，我依然赤手空拳制作网站](https://juejin.im/post/5c74ad81f265da2da00ebaf6)

这篇博客的作者是 Caddy 以及多个其他知名开源项目的作者（虽然他在博客里装弱）。

在这篇博客里，作者质疑了现在的前端生态为了创建一个简单的网站却要先下载动辄几百兆的文件。而前端已经复杂到，即使是工资很高、工作年限很久的前端工程师在很多地方依旧不明不白。

之后他还用自己写的几个页面来做了演示，说明了完成同样的功能，其实完全不需要加载好几兆的框架文件。

在我看来，浏览器给了前端太多的灵活性，反而让前端不知道该如何选择了。从仅靠“约定大于配置”的思路的库能获得广泛的使用就能看出两点：一是前端可用的方案太多了，配置也太杂了；二是现在的前端工程师也对此深恶痛绝，因此想要寻求解决这种碎片化配置的方案。

## 新闻

### [由于权限歧义，导致阿里云代码托管平台很多企业私密代码暴露](https://www.v2ex.com/t/537559)

阿里云代码托管平台是基于 gitlab 的套壳版，gitlab 一般应用于企业，internal 的意思毫无疑问的就是“企业内用户可见”。而阿里云代码托管平台由于面向的是所有注册用户，因此 internal 的意思就出现了歧义。

## 技术杂谈

### [自动生成人脸](http://www.whichfaceisreal.com/)

这个网站每次打开都会自动生成一张世界上并不存在的人脸照片，与另一个真实存在的人的照片摆在一起让你判断。

### [自动生成二次元妹子](https://www.thiswaifudoesnotexist.net/)

这个网站可以帮你创造老婆，不过据我观察，有时候它也会玩脱了创造出奇怪的东西。

### [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html)

软件使用目录的一种规范。

### [docker-airflow-celery](https://github.com/MeiK2333/docker-airflow-celery)

之前我曾介绍过 Airbnb 开源的任务调度系统 Airflow，这是可用于创建分布式 Airflow 的 Dockerfile，可以快速启动一个 Master 节点与大量的 Worker 节点。

## 视频分享

### Fate/Grand Order 清廉なるHeretics

<video src="/weekly15/videoplayback.mp4" controls="controls" width="100%">
Your browser does not support the audio tag.
</video>

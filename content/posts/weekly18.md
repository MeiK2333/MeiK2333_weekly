---
title: 每周分享第 18 期
date: 2019-03-28 14:53:37
tags:
---

记录我过去一周看到的值得分享的东西，每周四发布。

<!--more-->

## 随笔

### [gail.com](https://gail.com/)

由于与谷歌的邮箱域名（gmail.com）相近，每周有超过一百二十万封邮件被发往这个网址。

### [996.icu](https://996.icu/#/zh_CN)

什么是 996.ICU？工作 996，生病 ICU。

## 新闻

### [真的有删库跑路的程序员出现了](https://www.oschina.net/news/105494/ahauto-page-crack)

现在打开这个网站，只有一张静态图片了……

## 技术杂谈

### [为何蔡徐坤每条微博转发量 100 万+？用大数据扒一扒他的真假流量粉](https://www.v2ex.com/t/548359)

用大数据分析 CXK 的流量粉。

我之前曾经想干过类似的事情，就是使用爬虫爬取大量的数据进行分析，不过没有什么好的目标，最终还是作罢了……

### [moonlight-stream](https://github.com/moonlight-stream)

moonlight-stream 可以让你建立自己的流游戏服务器，只要在服务器上搭建好服务，就可以在各种设备上畅玩游戏了。

### Python 修改类的只读属性

Python 可以通过 `@property` 或者修改 `__setattr__` 来为类定义只读方法，但只读的方法依旧是可以被修改的。

比如我们现在想要修改闭包函数绑定的参数，这个参数在 Python3.7 以前都是只读的：

```python
def makefunc(a):
    def func(b):
        return a + b
    return func
```

```python
>>> f = makefunc(1)
>>> f.__closure__[0].cell_contents = 2
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
AttributeError: attribute 'cell_contents' of 'cell' objects is not writable
```

但我们仍可以用 C API 的方式来修改这个属性：

```python
>>> import ctypes
>>> PyCell_Set = ctypes.pythonapi.PyCell_Set
>>> PyCell_Set.argtypes = (ctypes.py_object, ctypes.py_object)
>>> PyCell_Set.restype = ctypes.c_int
>>> ctypes.pythonapi.PyCell_Set(f.__closure__[0], 2)

>>> print(f(1))
3
>>> print(f(2))
4
```

## 视频分享

一时鸽一时爽，一直鸽一直爽。

### 96猫 『嘘の火花』

<video src="/weekly18/96猫『嘘の火花』.mp4" controls="controls" width="100%">
Your browser does not support the audio tag.
</video>

### 喵

<video src="/weekly18/56a7ca01cb631f498d147f5ea6290a84.mp4" controls="controls" width="100%">
Your browser does not support the audio tag.
</video>

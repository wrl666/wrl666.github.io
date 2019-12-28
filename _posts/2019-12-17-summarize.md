---
title: 对定时器,BOM，DOM知识总结
category: js
picture: /public/img/p4.png
layout: content  
---

定时器setInterval()：按照指定的周期（以毫秒计）来调用函数或计算表达式。方法会不停地调用函数，直到 clearInterval() 被调用或窗口被关闭。

## BOM 浏览器操作
window对象 
open();      
close();
alert();
prompt()
confirm();

## location
location.reload();  重载 刷新
location.replace();  替换(url) 跳转了网页 会覆盖历史记录 
location.href = ''      跳转了网页

## history
history.back();  返回上一页
history.forward();前进
history.go() 前进(正数)或后退(负数)

## 定时器
一次性setTimeout(function, time)
周期性setInterval(function, time)

取消定时器clearTimeout(index)和clearInterval(index)



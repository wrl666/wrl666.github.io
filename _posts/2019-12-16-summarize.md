---
title: 初步了解对象与this的指向
category: js
picture: /public/img/p5.jpg
layout: content  
---

JavaScript中的所有事物都是对象：字符串、数字、数组、日期等等。<br>
在 JavaScript 中，对象是拥有属性和方法的数据。

## 对象
1.对象值用逗号分开写
2.由一个名字对应一个值
3.对象是一个无序的集合
4.同名后面会覆盖前面
5.对象的复制，其实是复制的地址
6.对象判断一定为真
7.俩个对象，即使里面的内容完全一样，但是判断其相等是，为false，数组也是这样

1.初始化一个对象
var obj = new Object();
2. 给对象添加你内容：
obj.tel = tel;
3. 返回生成的对象
 return obj;


## this表示当前对象的关键变量
1.在全局作用域下 this对象指向的是window对象
2.在对象里面this的指向是当前该对象
3.new 会改变 this 指向 ，自动创建一个对象, 并且把 this 指向到创建的这个对象 

[TOC]

HTML (HyperText Markup Language) 是可以被浏览器渲染的标记语言。

> 参考文档：[MDN](https://developer.mozilla.org/zh-CN/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

> 源码：[lesson1](lesson01.html)

## HTML 元素
![元素](https://media.prod.mdn.mozit.cloud/attachments/2019/02/08/16475/cfa4526491ae15e6256fd67bb16bc7ea/element.png)

## 嵌套元素

嵌套元素：元素嵌套元素

```
<p>我的猫咪脾气<strong>爆</strong>:)</p>
```

## 块级元素
块级元素：以块的新式显示，会另起一行显示内容，比如段落
```
<p>段落</p><p>段落</p>
```

[块级元素有哪些？](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Block-level_elements)

## 内联元素
内联元素:不会独立使用一行显示，也不会换行，而是继续在其他的后面直接显示，比如加粗 

```
<strong>加粗</strong><strong>加粗</strong>
``` 

[内联元素有哪些？](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Inline_elements)

## 空元素
空元素：不一定有开始和结束标签的元素，比如图片
```
<img src="https://raw.githubusercontent.com/mdn/beginner-html-site/gh-pages/images/firefox-icon.png">
```
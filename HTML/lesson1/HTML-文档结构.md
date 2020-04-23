[TOC]

HTML (HyperText Markup Language) 是可以被浏览器渲染的标记语言。

## HTML - 文档结构

``` 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>这是标题</title>
</head>
<body>
<p>这是内容</p>
</body>
</html>
```

- `<!DOCTYPE html>` : 文档声明
- `<html>` : 文档内容根元素
- `<head>` : 文档头
- `<meta>` : 元数据：描述数据的数据
- `<body>` : 文档内容

## 文档特殊字符
有些特殊字符在HTML文档内，是无法直接显示的

- `<` => `&lt;`
- `>` => `&gt;`
- `"` => `&quot;`
- `'` => `&apos;`
- `&` => `&amp;`
- ` ` => `&nbsp;`

## 提高搜索引擎靠前
```
<meta name="description" content="This test Html">
```

Google Search Console配置
[Google Search Console](https://search.google.com/search-console/welcome?hl=zh-CN)

## 自定义站点图标
- 大小：16 x 16 像素，一般还会适配其他尺寸的，为了可以在其他设备上使用
- 格式：.ico格式

```
<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
```

## 引入js和css的方法
css:

```
<link rel="stylesheet" href="my-css-file.css">
```

js:
```
<script src="my-js-file.js"></script>
```
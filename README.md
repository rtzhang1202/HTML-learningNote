# HTML学习笔记

来源：[https://www.w3school.com.cn/html](https://www.w3school.com.cn/html)
***
## 基本语法
### 1、语法入门
元素成对存在，必须存在的元素:`<html></html>`，最好全部使用小写
（以下元素词语默认按照上条格式）
全局属性[在此](https://www.w3school.com.cn/tags/index.asp)。

1、 **body**: 表示主体，该元素中间的内容会被显示
- `<hr/>`可以创建水平线
- `<!--注释-->`用于创建注释
  

2、**h1、h2、h3**: 表示HTML标题，从1到3大小逐次递减，最小为6
  

3、 **p**: 表示段落
- `<br/>`可以在一个段落内换行
- 无法通过在 HTML 代码中添加额外的空格或换行来改变输出的效果
  

4、 **table**: 定义表格
  

5、文本格式化  
点击[此处](https://www.w3school.com.cn/html/html_formatting.asp)跳转到教程界面，以下为常用
- `<pre>`: 保留换行与空格的文本，适合显示计算机代码
- `<code>`: 适合书写代码
- `<a href="link">LinkText></a>`: 表示链接/地址
- `<q>`、`<blockquote>`: 分别表示短、长的引用文，在元素中可以用site=“link”来表示引用源地址
  

6、**a**: 表示链接  
可以嵌套在其他元素内，使用示例：
`<a herf="link">text</a>`，不写完整链接可以指向本站链接，写完整链接可以跳转外部链接<br/>text处也可以使用img元素，用图片来代表链接
- `target`属性: =“”中写 _blank可以在新窗口打开链接
  

7、**img**: 插入图片<br>
只包含属性，没有闭合标签，直接书写为`<img src="url" alt="text"/>`  
[`<map>`](https://www.w3school.com.cn/tags/tag_map.asp)、
[`<area>`](https://www.w3school.com.cn/tags/tag_area.asp)的示例


### 2、HTML属性
<br>

属性的一般使用格式为 `style=“something”`

<br>

1、 **style属性**
使用示例：`<body style="background-color:yellow">`
<br\>`<h2 style="background-color:red ; font-size:14px">This is a heading</h2>`

- `background-color` 属性为元素定义了**背景颜色**,颜色以名称或者代码表示
- `font-family` 属性定义文本的**字体**
- `font-size` 属性定义文本的**字体尺寸**
- `text-align` 属性规定了元素中文本的水平对齐方式
  - center: 居中
  - end: 居右
  - justify: 居左
  
2、**图片相关属性**
- `src` 属性在img元素内定义图片的URL地址，例如[http://www.w3school.com.cn/images/boat.gif](http://www.w3school.com.cn/images/boat.gif)
- `align` 属性在img元素内定义图片格式在=“”中填入
  - bottom 底部对齐（默认）
  - middle 中间对齐
  - top 顶部对齐
  - left 图片贴左
  - right 图片贴右
- `alt` 属性定义替换文本，通常在图片无法显示的时候显示
- `backgroud` 属性写在body内定义背景图片
- `width`、`height` 属性在img元素内定义图片尺寸


***
## HTML CSS
1、使用`<head>`对HTML进行格式化,连接外部样式表详见[此处](https://www.w3school.com.cn/html/html_css.asp)
```html
<html>
    <head>
    <style type="text/css">
    h1 {color:darkslategray ; font-family: initial; text-align:center}<!--指定h1元素的格式-->
    p {color: blue}<!--指定p元素的格式-->
    </style>
    </head>
</html>
```

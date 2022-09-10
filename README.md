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

### 2、HTML属性
1、 style属性
使用示例：`<body style="background-color:yellow">`
<br\>`<h2 style="background-color:red ; font-size:14px">This is a heading</h2>`
- background-color 属性为元素定义了**背景颜色**,颜色以名称或者代码表示
- font-family 属性定义文本的**字体**
- font-size 属性定义文本的**字体尺寸**
- text-align 属性规定了元素中文本的水平对齐方式
  - center: 居中
  - end: 居右
  - justify: 居左
  

***
## HTML CSS
1、使用`<head>`对HTML进行格式化
`<html>

<head>
<style type="text/css">
h1 {color: red}
p {color: blue}
</style>
</head>

<body>
<h1>header 1</h1>
<p>A paragraph.</p>
</body>

</html>`

# CSS

CSS全称为“层叠样式表 (Cascading Style Sheets)”，它主要是用于定义HTML内容在浏览器内的显示样式，如文字大小、颜色、字体加粗等。

| | |
|---|---|
| 用css样式，为表格加入边框 | `<style type="text/css">`<br/> `table tr td,th{border:1px solid #000;}`<br/> `</style>` |
|设置文字字号|font-size:20px;|
|设置文字颜色|color:red;|
|设置字体加粗|font-weight:bold;|
|注释|`/*zhushi*/`|
## 内联式 css 样式

内联式css样式表就是把css代码直接写在现有的HTML标签中，如下面代码：

`<p style="color:red">这里文字是红色。</p>`

## 嵌入式 css 样式

嵌入式css样式，就是可以把css样式代码写在`<style type="text/css"></style>`标签之间。如下面代码实现把三个<span>标签中的文字设置为红色：

`<style type="text/css">
span{
color:red;
}
</style>`

## 外部式 css 样式

外部式 css 样式(也可称为外联式)就是把 css 代码写一个单独的外部文件中，这个 css 样式文件以“.css”为扩展名，在 `<head>` 内（不是在 `<style>` 标签内）使用 `<link>` 标签将 css 样式文件链接到 HTML 文件内，如下面代码：

`<link href="base.css" rel="stylesheet" type="text/css" />`

注意：

1、css样式文件名称以有意义的英文字母命名，如 main.css。

2、`rel="stylesheet" type="text/css"` 是固定写法不可修改。

3、<link>标签位置一般写在<head>标签之内。

<input type="button" value="普通按钮" />
			<button>button按钮</button>
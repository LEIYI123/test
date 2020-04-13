# 前端基础认识



## 前端工具

### 编辑器

- hbuilder x
- webstorm
- vscode
- sublime text



### 浏览器

#### 主流浏览器：拥有独立内核的浏览器

- chrome内核：blink（webkit）
- safari（苹果）- webkit
- IE - Trident
- firefox（火狐）- Gecko
- opera - blink（persto）

## HTML常用标签

HTML全称：HyperText Markup Language

### 标题 - `h1-h6`

作用： 给内容设置标题语义，h1 到 h6 重要性依次递减

注意：在 HTML5 以前，h1 标签在页面只能使用一次（SEO）, h1 一般用在文章标签或者网站的LOGO

### 段落 - `p` 

作用： 给内容设置段落语义

### 水平线 - `hr` 

### 换行 - `br`

###  实体字符

- 英文空格 ：`&nbsp`
- 中文空格： `&emsp`
- 小写： `&lt`
- 大于 ： `&gt`

### 图片 - `img`

作用： 插入一张图片

```html
<img src="图片地址" alt="图片加载失败是显示的提示性文本">
```

### 超链接 - `a（anchor）` 

作用

- 锚点

- 链接

  href : 跳转地址

  target : 新窗口打开方式

  ​           _self : 默认值，本窗口打开

  ​           _blank : 新窗口打开

- 打电话 / 发邮件

- 协议限定符

### 基准网址标记 - `base`

它是一个单标签，位于网页头部文件的head标签内，一个页面最多只能使用一个base元素，用来提供一个指定的默认目标，也算是一种表达路径和连接网址的标记。

```html
浏览器解析时会在路径前加上base给的目标，而页面中的相对路径也都转换成了绝对路径。使用了base标签就应带上href属性和target属性。
```

- base href：跳转地址
- base target：网页窗口打开方式
  1. _blank：在新窗口打开
  2. _parent：在上一级窗口打开
  3. _self：默认值，在当前窗口打开
  4. _top：在浏览器的整个窗口打开链接，忽略任何框架



### 列表

- 无序列表 \- `ul` (使用最多的)：内容是一个整体，其内部为一个个子项，切没有顺序
- 有序列表 \- `ol` （少）
- 定义列表 \- `dl` （少）

### 无语义标签 `div / span` 

`div` 和 `span` 本身是没有意义，他们的最大意义在于因为没有语义而可以随意使用来作为布局的包裹块。

### 表格 - `table` 

### 表单 - `form` 

```html
<form action="" method="">

</form>
```

action: 数据提交的方式

method：提交方式 - Get / Post

​              本身是没有区别的，所拥有的区别是浏览器导致的。

​              get  提交数据显示在地址栏上，post   不显示

​              get  提交的数据量有限，如图片，文件等数据就有可能无法提交。

### `input   type`

- text   文本框
- password   密码框
- radio   单选
- checkbox   多选
- submit   提交
- reset    重置

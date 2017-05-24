# GitHub Flavored Markdown 语法详解
### 标题
***
大标题一般用于显示工程名，只要在标题下面跟上===即可（=个数大于2）<br>
```
标题
===
```
中标题一般显示重点项，只要在标题下面输入----即可（-个数大于2）<br>
```
requirements
-----------
```
小标题以#号为开头，分为6个级别，注意#号和标题之间要有空格
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
### 斜体
***
可以使用*号或者_号包围文字
例如 *Deep Learning* 、_斜体_
### 加粗
***
用两个*或者_号包围文字，达到加粗字体的效果。
例如， **Deep Learning ** 、 __我怎么变粗了__
如果*号和_号两边都有空白的话，它们会被当成普通的符号使用
### 删除线
***
用两个~包围文本，达到删除线的目的
例如，~~你看我被删除了吗？~~

### 单行文本
***
	我是单行文本
在一行开头加入一个Tab或者4个空格。   
### 多行文本（文本块）
***
使用一对各三个的反引号```
演示
```
使用反引号即可
这是代码块
```
### 文字高亮
***
文字高亮功能可使行内部分文字高亮，使用一对反引号。
`看我亮不？`
### 换行
***
直接回车无法换行 ，可以在上一行文本后面补三个空格。
### 图片
***
	格式为：![alt](URL title)
alt和title即对应HTML中的alt和title属性（都可省略）
alt表示图片显示失败时的替换文本
title表示鼠标停留在图片时的显示文本（注意这里要加引号）
URL即为图片的url地址，如果引用本repo中的图片，直接使用**相对路径**即可，如果引用其他repo中的图片注意格式：`仓库地址/raw/分支名/图片路径`.
![图片显示失败](http://wx2.sinaimg.cn/large/77ba098bgy1ffr3i7d3zij21kw167wx1.jpg "鲸鱼座")
### 链接
***
#### 链接外部URL
Markdown 支持两种形式地链接语法：行内式和参考式两种形式
不管是哪种形式，链接文字都是用方括号[]来标记，要建立一个**行内式**的链接，只要在方括号后面紧跟着圆括号并插入网址链接即可，如果好像要加上链接的title文字，只要在网址后面用双引号将title包围起来，例如：
[知乎](https://www.zhihu.com/ "首页")<br>
当然，链接文字和title文字都是可选的，例如：
https://www.zhihu.com/

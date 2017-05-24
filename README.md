GitHub Flavored Markdown 语法详解
================================
### 标题
-------
- 大标题一般用于显示工程名，只要在标题下面跟上===即可（=个数大于2）
- 中标题一般显示重点项，只要在标题下面输入----即可（-个数大于2）
- 小标题以#号为开头，分为6个级别，注意#号和标题之间要有空格
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

### 斜体
-------
|#|语法|效果|
|----|---|-------|
|1|`*我怎么斜了*`|*我怎么斜了*|
|2|`_歪头_`|_歪头_|
### 加粗
-------
|#|语法|效果|
|---|---|---|
|1|`**Deep learning**`|**Deep learning**|
|2|`__你看我粗吗__`|__你看我粗吗__|
### 删除线
----------
|语法|效果|
|---|---|
|`~~我被删除了吗?~~`|~~我被删除了吗~~|
### 单行文本
-----------
	我是单行文本
在一行开头加入一个Tab或者4个空格。   
### 多行文本（文本块）
-------------
使用一对各三个的反引号
```
使用反引号即可
这是代码块
```
### 文字高亮
------------
文字高亮功能可使行内部分文字高亮，使用一对反引号。   
`看我亮不？`
### 换行
-------
直接回车无法换行 ，可以在上一行文本后面补三个空格。   
或者用html标签**br**
### 图片
--------
	格式为：![alt](URL title)
alt和title即对应HTML中的alt和title属性（都可省略）:
- alt表示图片显示失败时的替换文本
- title表示鼠标停留在图片时的显示文本（注意这里要加引号）
URL即为图片的url地址，如果引用本repo中的图片，直接使用**相对路径**即可，如果引用其他repo中的图片注意格式：**仓库地址/raw/分支名/图片路径**   

|#|语法|效果|
|---|---|---
|1|`![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")`|![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")
|2|`![](http://www.baidu.com/img/bdlogo.gif)`|![](http://www.baidu.com/img/bdlogo.gif)
### 链接
--------
Markdown 支持两种形式的链接语法：行内式和参考式两种形式   
**行内式语法:**   
    [alt](url title)
 - alt显示链接文字
 - title表示鼠标停留在链接时显示的文字
其中alt和title都可以省略   
   
|#|语法|效果|
|--------|-----------------|------------|
|1|`[知乎](https://www.zhihu.com/ "首页")`|[知乎](https://www.zhihu.com/ "首页")|
|2|`https://www.zhihu.com/`|https://www.zhihu.com/|   

**参考式语法：**   
    [alt][id]
- alt 显示链接文字
- id表示用于辨识链接的标记
然后在文件任意处把id标记的链接内容定义出来   
   
|#|语法|效果|
|---|---|---|
|1|`[知乎][zhihu(or other id)]  [zhihu]: https://www.zhihu.com/`|[知乎][zhihu] [zhihu]: https://www.zhihu.com/|

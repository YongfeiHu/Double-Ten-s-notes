# 1.MarkDown基本语法 {#1}  
[TOC] 
## 1.0 换行及特殊字符
   行尾加入2个或多个空格后，然后按回车，即可创建一个换行（`<br>`）,建议直接使用`<br>`,因其可见，为输入方便可用两个空格+回车。  
    对于 Markdown 中的语法符号，前面加反斜线\即可显示符号本身
## 1.1 标题
### 1.11 使用#号标记标题语法格式：
```markdown
# 一级标题    
## 二级标题   
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

显示效果如下：
# 一级标题     
## 二级标题  
### 三级标题  
#### 四级标题  
##### 五级标题
###### 六级标题



### 1.1.2 使用HTML语法来表示一级及二级标题

```markdown
<h1>一级标题</h1>
<h2>二级标题 </h2>
```

显示效果如下：
<h1>一级标题</h1>
<h2>二级标题 </h2>

### 1.1.3 使用=====表示一级标题，使用----表示二级标题

```markdown
一级标题
=====


二级标题
-----
```
显示效果如下：

一级标题
=====


二级标题
-----

## 1.2 字体
### 1.2.1 粗体、斜体、删除线等
```markdown
    *斜体文字*  
    _斜体文字_  
    **粗体文字**  
    __粗体文字__  
    <b>HTML加粗内容示例</b>  
    <strong>HTML加粗文字</strong>  
    ***粗斜体文字***  
    __粗斜体文字__  
    ~~删除文字~~
    ~~Markdown 删除线内容~~  
    <s>删除线内容</s>  
    <u>下划线文字</u>  


```

显示效果如下：<br>
    *斜体文字*  
    _斜体文字_  
    **粗体文字**  
    __粗体文字__  
    <b>HTML加粗内容示例</b>  
    <strong>HTML加粗文字</strong>  
    ***粗斜体文字***  
    __粗斜体文字__  
    ~~删除文字~~
    ~~Markdown 删除线内容~~  
    <s>删除线内容</s>  
    <u>下划线文字</u>  

## 1.2.2 字体、字号和颜色
使用HTML语法
```markdown
 
    <small>小号文字</small>  
    <large>字号增大</large>  

```
效果如下：<br>
<big>大号文字</big>      
<small>小号文字</small>  
<large>字号增大</large>  

### 1.2.3 字体背景颜色
使用HTML语法 (方法未生效)
```markdown
    <table><tr><td bgcolor=orange>背景色是：orange</td></tr></table>


```
效果如下：<br>

<table><tr><td bgcolor=orange>背景色是：orange</td></tr></table>



## 1.3 链接语法  
### 1.3.1 markdown链接语法
```markdown
    [百度](https://www.baidu.com)
    带Tip文字的链接
    [百度](https://www.baidu.com "search")
    [百度一下，你就知道](https://www.baidu.com "搜索网站")  

```

显示效果如下  
[百度](https://www.baidu.com)
[百度](https://www.baidu.com "search")  
[百度一下，你就知道](https://www.baidu.com "搜索网站")  

    
### 1.3.2 HTML链接方式的语法

```markdown
    <a href="baidu.com" title="搜索网站">百度一下，你就知道</a>  

```
效果如下  

<a href="baidu.com" title="搜索网站">百度一下，你就知道</a>  

### 1.3.3 图片链接

```markdown
    下面通过超链接引用图片
    ![百度logo](https://www.baidu.com/img/flexible/logo/pc/result.png)  

    下面的图片也是超链接
    [![百度logo](https://www.baidu.com/img/flexible/logo/pc/result.png)](www.baidu.com)  
    
    自动生成超链接
     <https://www.baidu.com/>
```
效果如下  
    ![百度logo](https://www.baidu.com/img/flexible/logo/pc/result.png)  
    [![百度logo](https://www.baidu.com/img/flexible/logo/pc/result.png)](https://www.baidu.com/)  
    <https://www.baidu.com/>

### 1.3.4 页内链接（锚点）
```markdown
    ## 这是我的标题{#index}   //在某个标题后面设置锚点
    
    跳转到[页内链接（锚点）](#1)		//回到锚点

```
显示效果  
跳转到[页内链接（锚点）](#1)		//回到锚点

## 1.4 分割线
如下符号大于3个，且不能包含其它内容即为分割线
```markdown

-------------  
*************
—————————————
```

显示效果：  

-------------  
*************
—————————————

## 1.5 代码语法
### 1.5.1 包裹转义代码
```markdown
    ``printf("hello world");``	//这是markdown语法
    <code>printf("hello world");</code> //这是HTML语法

```
显示效果：  
``printf("hello world");``	//这是markdown语法  
<code>printf("hello world");</code> //这是HTML语法  

### 1.5.2 代码块
```markdown
   直接用三个` ```来作为开始就好了。
    ```
        import os
        import re
    ```

```
显示效果：  
```
    import os
    import re
```

### 1.5.3 HTML代码块
```markdown
代码部分需要缩进

<html>  

    import os  

    import re
</html> 
或者
<head>  
    import os  

    import re  
</head>  

```
显示效果：  
<html>  

    import os
    import re  

</html>  

<head>  

    import os
    import re  
</head>  

## 1.6 引用
### 1.6.1 基本引用
```markdown
>这是一个引用  
>这是一个引用  
>这是一个引用  
>这是一个引用  
>  
>这是一个引用  

```
显示效果：  
>这是一个引用  
>这是一个引用  
>这是一个引用  
>这是一个引用  
>  
>这是一个引用  
>  
### 1.6.2 嵌套引用
```markdown
>这是一个引用  
>>这是一个引用  
>>这是一个引用  
>这是一个引用  
>>  2  
>>这是一个引用  

```
显示效果：  
>这是一个引用  
>>这是一个引用  
>>这是一个引用  
>这是一个引用  
>>  2  
>>这是一个引用  

## 1.7 列表
### 1.7.1 无序列表
建议使用 - 来做无序列表
```markdown
- 我是无序列表
- 我是无序列表
+ 我是无序列表
+ 我是无序列表
* 我是无序列表
* 我是无序列表

```
显示效果：  
- 我是无序列表
- 我是无序列表
+ 我是无序列表
+ 我是无序列表
* 我是无序列表
* 我是无序列表

### 1.7.2 有序列表
使用数字和一个英文句点表示有序列表。  
注意：英文句点后面一定要有一个空格，起到缩进的作用。
```markdown
1. 我是有序列表
2. 我是有序列表
3. 我是有序列表

```
显示效果：  
1. 我是有序列表
2. 我是有序列表
3. 我是有序列表

## 1.8 表格

建议使用 - 来做无序列表
```markdown
| 姓名  | 学号    | 分数 |  
|-----|-------|----|  
| 孙悟空 | 2021  | 95 |  
| 猪八戒 | 20211 | 96 |  


```
显示效果：  

| 姓名  | 学号    | 分数 |  
|-----|-------|----|  
| 孙悟空 | 2021  | 95 |  
| 猪八戒 | 20211 | 96 |  


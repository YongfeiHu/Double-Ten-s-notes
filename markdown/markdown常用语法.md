# 1.MarkDown基本语法
## 1.0 换行
   行尾加入2个或多个空格后，然后按回车，即可创建一个换行（`<br>`）,建议直接使用`<br>`,因其可见，为输入方便可用两个空格。
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
    *这里是文字*  
    _这里是文字_  
    **这里是文字**  
    ***这里是文字***  
    ~~这里是文字~~
```

显示效果如下：<br>
    *这里是文字*  
    _这里是文字_  
    **这里是文字**  
    ***这里是文字***  
    ~~这里是文字~~  

## 1.2.2 字体、字号和颜色
使用HTML语法
```markdown
    <font face='黑体' color=#ff0000 size=4>字体字号颜色</font>  
    <font face='黑体' color=#ffFF00 size=6>字体字号颜色</font>  
    <font face='黑体' color=#ff00FF size=8>字体字号颜色</font>  
    <font face='宋体' color=#00FFFF size=12>字体字号颜色</font>  
```
效果如下：<br>
    <font face='黑体' color=#ff0000 size=4>字体字号颜色</font>  
    <font face='黑体' color=#ffFF00 size=6>字体字号颜色</font>  
    <font face='黑体' color=#ff00FF size=8>字体字号颜色</font>  
    <font face='宋体' color=#00FFFF size=12>字体字号颜色</font>  

### 1.2.3 字体背景颜色
使用HTML语法
```markdown
    <table><tr><td bgcolor=orange>背景色是：orange</td></tr></table>  

```
效果如下：<br>

<table><tr><td bgcolor=#FFF000>背景色是：#FFF000</td></tr></table>  

## 1.3 链接语法  
### 1.3.1 markdown语法
```markdown
    [百度](baidu.com)
    [百度](baidu.com "search")
    [百度一下，你就知道](baidu.com "搜索网站")  


```

显示效果如下  
 [百度](baidu.com)  
 [百度](baidu.com "search")  
 [百度一下，你就知道](baidu.com "搜索网站")  

### 1.3.2 HTML方式的语法

```markdown
    <a href="baidu.com" title="搜索网站">百度一下，你就知道</a>  

```
效果如下  

<a href="baidu.com" title="搜索网站">百度一下，你就知道</a>  

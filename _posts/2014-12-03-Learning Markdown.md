---
 layout: defaultl
 title: Learning Markdown Note
---

#Markdown 学习笔记

##简介:

Markdown 为一个文本转html的标记语言，使用简单的文本就可以转化为XHTML/HTML．

>  Markdown 由两部分组成：
> 
>  *  文本语法
>  *  将文本转为HTML的转换器



-------------------------------------------------------------------------------

##语法:

-------------------------------------------------------------------------------

### 块元素

#### 段落

Markdown　默认的段落为不使用任何标记的字，连续的两个空行为&lt;br>

#### 标题

Markdown采取两种标记方法：<kbd>Setext</kbd>和<kbd>atx</kbd>．

**Setext** 采取=和-来标记两级标题．例如：

> `This is an H1`
> 
> `=============`
> 
> `This is an H2`
> 
> `-------------`

**atx** 采取#来标识６级标题．

> `# This is an H1`

> `## This is an H2`

#### 区块引言

Markdown采取email的 <kbd> > </kbd> 进行区块标记。在每行开始的位置标记。
区块标记可以嵌套使用，并且可以使用其他Markdown标记。例如：

> `> ## This is a Header`

>  

> `> 1. This is the first list item.`

> `> 2. This is the second list item.`

> `> Here's some example.`

> `>    return shell_exec("echo $input | $Markdown_script")`

显示如下：

> ## This is a Header

>  

> 1. This is the first list item.

> 2. This is the second list item.

> Here's some example.

>     return shell_exec("echo $input | $Markdown_script")


#### 列表 ####

Markdown中有两种列表：**有序列表** 和 **无序列表**。


**有序列表** 使用<kbd>数字+英文</kbd> . 标记即可。例如

> `1. Red`

> `2. Green`

> `3. Blud`

**无序列表** 使用 <kbd> + - * </kbd> . 标记。 例如

> `+ Red`

> `+ Green`

> `+ Blud`

#### 程序区块 ####
Markdown使用4个空格或者1个Tab键即可。

#### 分割线 ####
在一行中使用3个以上的 - , * 建立一个分隔线。

> `* * *`

> `***`

> `- - -`

> `-----------------`



-------------------------------------------------------------------------------

### 链接 ###

链接分为两种方式：行内，参考。

两种方式要显示的文字都使用方括号括起来，后续根据跟着不同的括号，分为行内还是参考
方式提供链接。

* 行内链接为：

    > `This is [an example](htp://example.com "Title") inline link`
    
    实际显示为：
    
    > This is [an example](htp://example.com "Title") inline link

* 参考方式:

    > 'This is [an example][id] reference-style link.'
    
    接着在任何一个地方要把参考的内容定义出来：
    
    > '[id]: http://example.com/' "Optional title Here"

参考链接定义：
* 方括号，括号里输入链接标示符，与参考链接中的id对应，如果参考链接中没有id，则与
  现实的字面 an example,对应即可
* 接着一个冒号
* 接着一个以上的空白或者tab
* 链接地址
* 可选的title



-------------------------------------------------------------------------------


### 图片 ###

与链接基本类似。差别为前面有一个<kbd>!</kbd>号.

### 参考 ###
[台湾markdown说明](http://markdown.tw/)
[markdown在线编译器](https://stackedit.io)


---
layout: post
title: Markdown基础用法的学习
categories: [markdown]
description: markdown 学习
keywords: markdown
---
# <center> Markdown基础用法的学习<center>
### MarkDown是什么?
&ensp;MarkDown是一种轻量级标记语言，创始人为约翰·格鲁伯（John Gruber）。它允许人们“使用易读易写的纯文本格式编写文档。MarkDown从推出至今已吸引了大量的粉丝，如大家经常用的为知笔记、简书、和开发者爱好的GitHub以及国内的CSDN等，都对MarkDown提供了支持。

### 使用MarkDown的有点
* 专注你的文字内容而不是排版样式。

* 轻松的导出 HTML、PDF 和本身的 .md 文件。

* 纯文本内容，兼容所有的文本编辑器与文字处理软件。

* 可读，直观。是个适合所有人的写作语言。

### 编辑工具

&emsp;在 ``MacOSX`` 上，建议你用Mou 。 Mou ：是款免费且十分好用的 Markdown 编辑器，它支持实时预览，既左边是你编辑的 Markdown ，右边会实时的生成预览效果。  
&emsp;在Windows上，建议你用MarkdownPad。MarkdownPad：的效果和Mou 一样甚至比它更强大，但是是收费的。  
&emsp;PS.如果你不追求实时预览效果的话，其实用记事本编写MarkDown也是一个不错的选择，另外在各大编译器中也有对应的MarkDwon编辑插件，如用在IntelliJ IDEA中MultiMarkDwon插件。

### MarkDown的使用

 ###### 如何设置标题
* #一级标题
* ##二级标题
一次类推，最多能有六个``#``,也就是六级标题

###### 关于字体
\*斜体字\*  
*斜体字*  

\*\*粗体字\*\*  
**粗体字**   

\*\*\*加粗加斜\*\*\*  
***加粗加斜Hale***  

 \~\~中划线\~\~  
 ~~中划线~~  

 ###### 设置语法高亮
 \``GitHub\`` 现在成了主流，不仅提供Git代码托管（取代SVN）、Issue追踪（取代JIRA）   
 ``GitHub``现在成了主流，不仅提供Git代码托管（取代SVN）、Issue追踪（取代JIRA)  
 在``（两个反引号）之间的文字会被高亮显示。

 ###### 关于列表
  * 无序列表  
   \*无序1  
   *无序1  

   \*无序2  
   *无序2

* 有序列表

 1. a
 2. b  
 ...


 ###### 关于引用

 引用 如果你需要引用一小段别处的句子，那么就要用引用的格式。

\> 例如这样  
 > 例如这样

 ###### 关于插入
  * 插入链接

  \[链接文字](链接地址)

  例如：
  [百度](https://www.baidu.com/)

  * 插入图片

  \!\[图片名字](图片地址)

  \!\[百度](https://www.baidu.com/img/baidu.gif)
  ![百度](https://www.baidu.com/img/baidu.gif)


  ###### 代码框

  使用```包裹代码

  \```
  public static voiid main(String[] args){
    System.out.println("Hello World");
}
\```

```
public static voiid main(String[] args){
  System.out.println("Hello World");
}
```

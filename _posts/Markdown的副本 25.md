---
layout: post
title: Markdown
permalink: /others/
---

date: 2016-05-14 09:32:27
------
#### 导语：
> [Markdown](https://zh.wikipedia.org/wiki/Markdown) 是一种轻量级的「标记语言」，它的优点很多，目前也被越来越多的写作爱好者，撰稿者广泛使用。
<!--more-->
看到这里请不要被「标记」、「语言」所迷惑，Markdown 的语法十分简单。常用的标记符号也不超过十个，这种相对于更为复杂的HTML 标记语言来说，Markdown 可谓是十分轻量的，学习成本也不需要太多，且一旦熟悉这种语法规则，会有一劳永逸的效果。：

###### [This is an example](id:anchor1)


<img src="../images/Markdown.png" alt="Markdown" height="42" width="84">

![Markdown](../images/Markdown.png)




## 一、认识 Markdown

在刚才的导语里提到，Markdown 是一种用来写作的轻量级「标记语言」，用户可以使用这些标记符号以最小的输入代价生成极富表现力的文档：譬如您正在阅读的这份文档，它用简洁的语法代替排版，而不像一般我们用的字处理软件 *Word* 或 *Pages* 有大量的排版、字体设置。它使我们专心于码字，用「标记」语法，来代替常见的排版格式。例如此文从内容到格式，甚至插图，键盘就可以通通搞定了。目前来看，支持 Markdown 语法的编辑器有很多，包括很多网站（例如[简书](https://jianshu.io)）也支持了 Markdown 的文字录入。Markdown 从写作到完成，导出格式随心所欲，你可以导出 HTML 格式的文件用来网站发布，也可以十分方便的导出 PDF 格式，这种格式写出的简历更能得到 HR 的好感。甚至可以利用 CloudApp 这种云服务工具直接上传至网页用来分享你的文章，全球最大的轻博客平台 Tumblr，也支持使用 Mou 这类 Markdown 工具进行编辑并直接上传。


### Markdown 官方文档
>这里可以看到官方的 Markdown 语法规则文档，当然，后文我也会用自己的方式，阐述这些语法在实际使用中的用法。

* [[创始人 John Gruber 的 Markdown 语法说明](http://daringfireball.net/projects/markdown/syntax)]

* [[Markdown 中文版语法说明](http://wowubuntu.com/markdown/#list)]


### 使用 Markdown 的优点
* 专注你的文字内容而不是排版样式。
* 轻松的导出 HTML、PDF 和本身的 .md 文件。
* 纯文本内容，兼容所有的文本编辑器与字处理软件。
* 可读，直观。适合所有人的写作语言。



### 我该用什么工具？
![UIysses](http://a2.mzstatic.com/us/r30/Purple1/v4/6f/8c/59/6f8c59b1-7de6-8b5d-428b-887552e61f0e/icon128.png)
![Mou iocn](http://mouapp.com/Mou_128.png)
![iA icon](http://a4.mzstatic.com/us/r30/Purple1/v4/d2/55/8f/d2558f09-97db-ae54-2190-0c6c26282a87/icon128.png)


[UIysses](http://www.ulyssesapp.com/)、[Mou](http://25.io/mou/)、[iA Writer](https://ia.net/writer) 这些应用都是基于单文档的管理方式，而 Ulysses Ⅲ 支持 Folder、Filter 的管理，一个 Folder 里面可以创建多个 Sheet，Sheet 之间还可以进行 Combine 处理。
![cmd-markdown-logo](https://www.zybuluo.com/static/img/logo.png)    
[Windows/Mac/Linux 全平台客户端](https://www.zybuluo.com/cmd/)
###### 什么是 Cmd Markdown

您可以使用很多工具书写 Markdown，但是 Cmd Markdown 是这个星球上我们已知的、最好的 Markdown 工具——没有之一 ：）因为深信文字的力量，所以我们和你一样，对流畅书写，分享思想和知识，以及阅读体验有极致的追求，我们把对于这些诉求的回应整合在 Cmd Markdown，并且一次，两次，三次，乃至无数次地提升这个工具的体验，最终将它演化成一个 **编辑/发布/阅读** Markdown 的在线平台——您可以在任何地方，任何系统/设备上管理这里的文字。
它使用简单的符号标记不同的标题，分割不同的段落，**粗体** 或者 *斜体* 某些文字，更棒的是，它还可以
### Mac 平台
* 在 Mac OS X 上，我强烈建议你用 Mou 这款免费且十分好用的 Markdown 编辑器，它支持实时预览，既左边是你编辑 Markdown 语言，右边会实时的生成预览效果，笔者文章就是 Mou 这款应用写出来的。

### Web 平台
* Web 端上，我强烈推荐 [简书](http://jianshu.io/) 这款产品，上面有无数热爱文字的人在不停的创造、分享。在 Web 端使用 Markdown 没有比简书更舒服的地方了，它同样支持左右两栏的实时预览，字体优雅、简洁。
* 同样是 Web 端，[Draftin](https://draftin.com/) 这款在线 MD 编辑器也近乎完美。

------
## 二、Markdown 语法的简要规则
### 引用
> ###### like this

其次，你也可在撰写过程中，使用
> ###### CMD+R


快捷键来快速打开文档，以随时查阅和学习语法。

### 制作一份待办事宜 [Todo 列表]
- [ ] <!--option+V 即可打出 √-->
- [ ]
- [x]
- [x]
- [x]

### Code
`code`
### Horizontal Rules
division line
***
---

* * *

- - - -

### font
*斜体* *emphasize* _emphasize_   
**粗体** **strong** __strong__

### email
<fasminelee@gmail.com>

### Tables
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

First Header | Second Header | Third Header
------------ | ------------- | ------------
Content Cell | Content Cell  | Content Cell
Content Cell | Content Cell  | Content Cell

| First Header | Second Header | Third Header |
| ------------ | ------------- | ------------ |
| Content Cell | Content Cell  | Content Cell |
| Content Cell | Content Cell  | Content Cell |

First Header | Second Header | Third Header
:----------- | :-----------: | -----------:
Left         | Center        | Right
Left         | Center        | Right

| 项目        | 价格    |  数量   |
| --------   | -----: | :----:  |
| 计算机      | \$1600 |   5     |
| 手机        |   \$12 |   12    |
| 管线        |    \$1 |  234     |

### Anchor

Click this [link](#anchor1) in the Preview view will auto scroll to the place of the destination anchor.

------
## 三、与 Markdown 相关的一些推荐
### 可配套使用的工具

* [Droplr](http://droplr.com/)
* [Cloudapp](http://www.getcloudapp.com/)
* [ezShare for Mac](https://itunes.apple.com/cn/app/yi-xiang/id672522335?mt=12&uo=4&uo=4&at=10lJSw)
* [围脖图床修复计划](http://weibotuchuang.sinaapp.com/)
* [马克飞象，专为印象笔记打造的 Markdown 编辑器，非常推荐](http://maxiang.info/)



### 相关文章阅读
* [为什么作家应该用 Markdown 保存自己的文稿](http://apple4us.com/2012/02/why-writers-should-use-markdown.html)
* [Markdown 写作浅谈](http://www.yangzhiping.com/tech/r-markdown-knitr.html)
* [Markdown 工具补完](http://www.appinn.com/markdown-tools/)
* [Drafts + Scriptogr.am + Dropbox 打造移动端 Markdown 风格博客](http://jianshu.io/p/63HYZ6)
* [图灵社区 - 怎样使用 Markdown](http://www.ituring.com.cn/article/23)
* [为什么我们要学习 Markdown 的三个理由](http://news.cnblogs.com/n/139649/)
* [Markdown 语法写作入门指南 by ibuick](http://ibuick.me/?p=4093)

------

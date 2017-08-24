---
layout: page
title: iOS 9.0以后网络请求异常
permalink: /
---

------
iOS 9.0以后网络请求异常处理
<!--more-->

date: 2016-05-07 16:32:50
> ### 报：
> App Transport Security has blocked a cleartext HTTP (http://) resource load since it is insecure. Temporary exceptions can be configured via your app's Info.plist file.
> ### 解决方法：
> 在Info.plist添加属性

```
App Transport Security Setting
Allow Arbitrary Loads boolean Yes
```
#### 以上就是iOS 9.0以后网络请求异常的全文介绍,希望对您学习和使用ios应用开发有所帮助.

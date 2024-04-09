+++
author = "Cicada000"
title = "Hugo短代码"
slug = "shortcodes"
date = "2023-12-31"
description = "来一些好玩的短代码"
tags = [
    "shortcode",
    "html",
    "themes"
]
categories = [
    "themes"
]
+++

## 阅前提示

&emsp;&emsp;由于转义字符貌似不起作用，为了防止代码块中的短代码被渲染，我将短代码的 &#123;&#123;<  和 >&#125;&#125; 中的尖括号和大括号之间添加了空格，在实际使用时无需添加空格。

## 使用aplayer短代码来插入APlayer播放器

&emsp;&emsp;参数server：音乐提供商，例如netease。

&emsp;&emsp;参数type：类型，例如song。

&emsp;&emsp;参数id：唯一的id号码。

```html
{{ < aplayer server="netease" type="song" id="518894020" > }}
```

{{< aplayer server="netease" type="song" id="518894020" >}}

## 使用updated-banner短代码来插入文章过时提示

&emsp;&emsp;参数day：日期，指定在文章发布多少日后显示此banner。

```html
{{ < updated-banner day="1"> }}
```

{{< updated-banner day="1">}}

## 使用banner短代码来插入普通Banner

&emsp;&emsp;参数icon：Material Icon中的Icon图标。

&emsp;&emsp;参数border：边框颜色。

&emsp;&emsp;参数background：Banner上部的背景颜色。

&emsp;&emsp;参数top：Banner标题文字。

&emsp;&emsp;参数bottom：Banner正文内容。

```html
{{ < banner icon="settings" border="#FFAE00" background="#ffa6005c" top="测试标题"  bottom="测试内容" > }}
```

{{< banner icon="settings" border="#FFAE00" background="#ffa6005c" top="测试标题"  bottom="测试内容" >}}

## 使用photo-row短代码来使图片处于同一行

```html
{{ < photo-row > }}
https://via.placeholder.com/500
https://img.cicada000.work/-65271da64549bbae.jpg
{{ < /photo-row > }}
```

{{< photo-row >}}
https://via.placeholder.com/500
https://img.cicada000.work/-65271da64549bbae.jpg
{{< /photo-row >}}
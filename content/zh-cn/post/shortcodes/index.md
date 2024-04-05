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

## 使用Aplayer短代码来插入APlayer播放器

&emsp;&emsp;参数server：音乐提供商，例如netease。

&emsp;&emsp;参数type：类型，例如song。

&emsp;&emsp;参数id：唯一的id号码。

```html
{{ < aplayer server="netease" type="song" id="518894020" > }}
```

{{< aplayer server="netease" type="song" id="518894020" >}}

## 使用Updated-Banner短代码来插入文章过时提示

&emsp;&emsp;参数day：日期，指定在文章发布多少日后显示此banner。

```html
{{ < updated-banner day="1"> }}
```

{{< updated-banner day="1">}}

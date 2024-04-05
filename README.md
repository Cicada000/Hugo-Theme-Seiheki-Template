# Hugo-Theme-Seiheki-Template

<center>
    <img src="resources/img/Ultrawide.png">
</center>

<p align="center">青碧，一个<s>简陋的</s>Hugo博客主题。</p>


## 开发进度

- [x] Archives页面
- [x] Tags页面
- [x] Search页面
- [x] CSS美化
- [x] 图片灯箱
- [x] TOC显示
- [x] Utterance评论
- [x] 移动端适配
- [x] 文章阅读时长统计
- [x] 网页页脚美化
- [x] i18n适配
- [x] 分页设置
- [x] 404页面完善
- [x] 来点有意思的Shortcode

## 主题配置

### 基本配置

&emsp;&emsp;下列配置为演示使用，请根据自己站点的实际状况进行修改。

config.toml
```
baseURL = 'https://seiheki-demo.cicada000.work'            # 网站域名
defaultContentLanguage = 'zh-cn'                           # 网页默认语言，目前支持zh-cn和en-us
title = 'Seiheki Demo Site'                                # 网站Title，请同步更改i18n文件夹下配置
theme = 'seiheki'                                          # 主题名称
hasCJKLanguage = true                                      # 是否有CJK字符

[params]
    subtitle = "This is a demo site."                      # 网站副标题，请同步更改i18n文件夹下配置
    favicon = "https://www.cicada000.work/favicon.png"     # 网站Favicon 
    fancybox = true                                        # 开启图片灯箱
    paginate = 10                                          # 每页文章数目

[params.Umami]                                             # Umami网站数据统计
  webpanel = ""                                            # 统计网站面板，空值默认为官网
  id = "84f6eb25-5dcd-4e2b-b500-37a6ac27f531"              # 网站的Website ID，空值不开启统计

[params.Utterances]                                        # 添加Utterances评论
  repo = "Cicada000/Blog-Comments"                         # 你的评论仓库，空值不启用评论

[markup]
  [markup.highlight]
    codeFences = true
    linenos = true
    linenosStyle = "inline"
  [markup.goldmark.renderer]
    unsafe = true

[outputs]
  home = ["HTML" , "RSS" , "JSON"]

[permalinks]
  page = "/:slug/"                                         # 文章链接由文章的slug字段决定

[taxonomies]
  tag = "tags"                                             # tag页面
  category = "categories"                                  # category页面

[languages.zh-cn]
  weight = 1
  contentDir = "content/zh-cn"
[languages.en-us]
  weight = 2
  contentDir = "content/en-us"
```

### 添加Shortcode

&emsp;&emsp;自行在主题文件夹下的shortcodes文件夹进行添加，目前已有的shortcode详见[演示网页](https://seiheki-demo.cicada000.work/post/shortcodes/)。

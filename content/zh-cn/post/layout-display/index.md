+++
author = "Cicada000"
title = "排版示例"
date = "2023-11-19"
description = "本篇文章旨在展示 Seiheki 主题的 Markdown 渲染能力，包括标题、段落、代码、公式、短代码等多种元素的排版效果。"
image = "test-image.png"
tags = [
    "markdown",
    "排版",
    "示例",
    "Seiheki",
]
categories = [
    "主题演示"
]
+++

# 开启探索之旅

欢迎使用 Seiheki 主题！这是一个为文字爱好者设计的 Hugo 主题，强调优雅的中文排版与流畅的交互体验。本篇文章将作为你的实验室，展示主题所有的视觉元素。

## 文本排版之美

### 段落与呼吸感

中国文字之美，在于其形，更在于其意。正如《论语》所云：“学而时习之，不亦说乎？有朋自远方来，不亦乐乎？人不知而不愠，不亦君子乎？” 在 Seiheki 中，我们为正文配置了舒适的行高与字间距，确保长文阅读不再是一种负担。

> 这是一个引言示例。在 Seiheki 中，引言采用了侧边栏设计，配合柔和的背景色，让它在正文中既显眼又不显突兀。
>
> 即使是多段落的引用，也能保持良好的视觉连续性。

### 强调与修饰

你可以轻松地使用 **粗体** 来突出重点，或者使用 *斜体* 来增加文学感。当然，如果你需要删除某些过时的内容，~~删除线~~ 也是必不可少的。如果你想让文字显得更加专业，`行内代码` 是个不错选择。

---

## 多级标题与 TOC 测试

通过侧边栏的 TOC（目录），你可以快速跳转到以下各个章节。请注意侧边栏在滚动时的放大高亮效果。

### 三级标题演示 A
这里是一些占位文本，用于拉长页面高度，以便测试滚动。

### 三级标题演示 B
再来一点文本。在 Seiheki 中，我们特别优化了中文标题的 ID 生成与匹配，确保点击和滚动追踪都能完美支持。

---

## 列表与交互

### 任务与步骤
1. **第一步**：安装 Hugo
2. **第二步**：克隆 Seiheki 主题仓库
3. **第三步**：开始撰写你的第一篇博客
   - 记得配置 `config.toml`
   - 尝试添加一张精美的封面图

### 无序列表
- 极简设计
- 响应式布局
- 优秀的中文排版支持
- 丝滑的移动端菜单

---

## 特色功能展示

### 代码高亮

Seiheki 集成了优雅的代码块渲染，支持行号显示。

```python
def fibonacci(n):
    """一个简单的斐波那契数列生成器"""
    a, b = 0, 1
    result = []
    while a < n:
        result.append(a)
        a, b = b, a + b
    return result

# 输出前 1000 以内的数
print(fibonacci(1000))
```

### 丰富的短代码

{{< banner icon="warning" border="#FFAE00" background="#ffa6005c" top="注意" bottom="这是一条测试信息" >}}

### 数学公式 (LaTeX)

我们完美支持 MathJax。无论是行内公式 $E=mc^2$，还是复杂的段落公式：

$$
\int_{a}^{b} f(x) \,dx = F(b) - F(a)
$$

$$
\bbox[10px, border:2px solid #268785]{
    \psi(x, t) = A e^{i(kx - \omega t)}
}
$$

### 表格排版

| 功能模块 | 描述                    | 状态   |
| :------- | :---------------------- | :----- |
| 搜索     | 基于 Fuse.js 的全站搜索 | 已完成 |
| 评论     | 集成 Utterances         | 已完成 |
| 统计     | 集成 Umami              | 已完成 |
| 暗色模式 | 自动适配系统主题        | 已完成 |

---

## 媒体演示

### 图片灯箱
点击下方图片即可唤起 Fancybox 灯箱进行查看。

![示例图片](https://img.cicada000.work/-65271da64549bbae.jpg)

### 多图排列
使用自定义短代码实现多图横向排列。

{{< photo-row >}}
https://img.cicada000.work/BlogImage/2022/EVA-Telephone-Pole/ep1-3.png
https://img.cicada000.work/BlogImage/2022/EVA-Telephone-Pole/ep1-3.png
https://img.cicada000.work/BlogImage/2022/EVA-Telephone-Pole/ep1-3.png
{{< /photo-row >}}

---

# 结语

感谢你阅读本示例。希望这能帮助你更好地了解 Seiheki 的无限可能。如果你有任何建议，欢迎前往 Github 提交 Issue。

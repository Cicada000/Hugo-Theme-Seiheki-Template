+++
author = "Cicada000"
title = "Layout Display"
date = "2023-11-19"
description = "一些排版示例。"
tags = [
    "markdown",
    "css",
    "html",
    "themes",
]
categories = [
    "themes"
]
+++

# Markdown 测试文章

欢迎使用这篇文章来测试您的Markdown渲染引擎！

## 标题

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

## 段落和强调

普通段落的文本会被简单地渲染。

*斜体文本* 或 _斜体文本_

**粗体文本** 或 __粗体文本__

***粗斜体文本*** 或 ___粗斜体文本___

## 列表

无序列表：

- 项目1
- 项目2
  - 子项目2.1
  - 子项目2.2

有序列表：

1. 第一项
2. 第二项
   1. 子项2.1
   2. 子项2.2

## 引用

> 这是一个引用段落。
>
> 引用可以有多个段落。

## 代码

`inline code`

代码块：

```python
def bubbleSort(arr):
    n = len(arr)
 
    # 遍历所有数组元素
    for i in range(n):
 
        # Last i elements are already in place
        for j in range(0, n-i-1):
 
            if arr[j] > arr[j+1] :
                arr[j], arr[j+1] = arr[j+1], arr[j]
 
arr = [64, 34, 25, 12, 22, 11, 90]
 
bubbleSort(arr)
 
print ("排序后的数组:")
for i in range(len(arr)):
    print ("%d" %arr[i])
```

## 表格

| 左对齐标题 | 居中对齐标题 | 右对齐标题 |
|:------------|:-------------:|------------:|
| 左对齐文本  | 居中对齐文本  | 右对齐文本  |
| 文本行2     | 更多内容      | 更多内容    |
| 文本行3     | 更多内容      | 更多内容    |

<br>

<center>

居中的表格

| 左对齐标题 | 居中对齐标题 | 右对齐标题 |
|:------------|:-------------:|------------:|
| 左对齐文本  | 居中对齐文本  | 右对齐文本  |
| 文本行2     | 更多内容      | 更多内容    |
| 文本行3     | 更多内容      | 更多内容    |

</center>

## 图片

![TestImage](https://via.placeholder.com/150)

![TestImage](https://via.placeholder.com/500)
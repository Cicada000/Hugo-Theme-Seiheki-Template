+++
author = "Cicada000"
title = "Typography example"
date = "2023-11-19"
description = "Some Markdown rendering examples."
image = "test-image.png"
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

# Markdown Test Passage

Welcome to use this article to test your Markdown rendering engine! Click this [link](https://github.com/Cicada000/Hugo-Theme-Seiheki-Template) to access the Github repository for this theme.

## Heading

# First level title
## Second level title
### Level 3 heading
#### Level 4 heading
##### Level 5 heading
###### Level 6 heading

## Paragraphs and emphasis

Normal paragraph text is simply rendered.

*italicized text* or _italicized text_

**bold text** or __bold text__

***bold italic text*** 或 ___bold italic text___

## List

Unordered list:

- item 1
- item 2
  - Sub-item 2.1
  - Sub-item 2.2

Ordered list：

1. First item
2. Second item
   1. Sub-item 2.1
   2. Sub-item 2.2

## Quote

> This is a quoted passage.
>
> Quotes can have multiple paragraphs.

## Code

`inline code`

Code Block：

```python
def bubbleSort(arr):
    n = len(arr)
 
    # Iterate through all array elements
    for i in range(n):
 
        # Last i elements are already in place
        for j in range(0, n-i-1):
 
            if arr[j] > arr[j+1] :
                arr[j], arr[j+1] = arr[j+1], arr[j]
 
arr = [64, 34, 25, 12, 22, 11, 90]
 
bubbleSort(arr)
 
print ("sorted array:")
for i in range(len(arr)):
    print ("%d" %arr[i])
```

## Table

| Left-aligned title | Center-aligned title | Right-aligned title |
|:----------------|:-------------:|----------------:|
| Left-aligned text | Center-aligned text | Right-aligned text |
| Text line 2 | More content | More content |
| Text line 3 | More content | More content |

<br>

<center>

Centered table

| Left-aligned title | Center-aligned title | Right-aligned title |
|:----------------|:-------------:|----------------:|
| Left-aligned text | Center-aligned text | Right-aligned text |
| Text line 2 | More content | More content |
| Text line 3 | More content | More content |

</center>

## Picture

![TestImage](https://via.placeholder.com/150)

![TestImage](https://via.placeholder.com/500)
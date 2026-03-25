+++
author = "Cicada000"
title = "Typography Showcase"
date = "2023-11-19"
description = "A comprehensive demonstration of Markdown rendering, including titles, blockquotes, code, and custom shortcodes."
image = "test-image.png"
tags = [
    "markdown",
    "typography",
    "demo",
    "themes",
]
categories = [
    "showcase"
]
+++

# Welcome to Seiheki

Seiheki is a Hugo theme designed for writers who appreciate minimalist design and professional typography. This page serves as a comprehensive test of all supported Markdown elements and custom shortcodes.

## The Art of Typography

### Paragraphs and Spacing

Typography is the craft of endowing a human language with a durable visual form. As Robert Bringhurst famously wrote: "Typography must often draw attention to itself before it can be read." In Seiheki, we prioritize a comfortable reading experience with optimized line-height and letter-spacing.

> "A good writer should be a good reader, and a good reader should be a good critic."
>
> Blockquotes in Seiheki are designed with a subtle accent border and soft background, making them stand out while maintaining overall visual harmony.

### Emphasis and Styling

Use **bold text** to highlight key points or *italic text* for emphasis. For outdated information, ~~strikethrough text~~ is available. Technical terms like `inline code` are also elegantly supported.

---

## Navigation & TOC Test

The Table of Contents (TOC) on the right sidebar will automatically highlight your current reading progress as you scroll through this article.

### Section A: Scrolling Test
This section contains placeholder text to increase the page height and test the TOC scrollspy feature.

### Section B: Dynamic Highlighting
Seiheki supports smooth scrolling and dynamic TOC highlighting. Click on any item in the sidebar to jump directly to that section.

---

## Lists and Interactions

### Getting Started
1. **Prerequisite**: Install Hugo on your machine.
2. **Setup**: Clone the Seiheki theme repository.
3. **Write**: Create your first content file under `content/`.
   - Configure your `config.toml` properly.
   - Add a high-quality cover image.

### Features Checklist
- Minimalist and Clean Design
- Full Responsive Layout
- Optimized Multilingual Support
- Smooth Mobile Navigation

---

## Powerful Features

### Code Highlighting

Seiheki provides elegant code blocks with syntax highlighting and line numbers.

```javascript
function greet(name) {
    console.log(`Hello, ${name}! Welcome to Seiheki.`);
}

// Example usage
greet("World");
```

### Custom Shortcodes

{{< banner icon="warning" border="#FFAE00" background="#ffa6005c" top="Warning" bottom="This is a test message" >}}

### Mathematics (LaTeX)

We fully support MathJax for academic and technical writing. From simple inline formulas like $E=mc^2$ to complex block equations:

$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

$$
\bbox[10px, border:2px solid #268785]{
    \nabla \cdot \mathbf{E} = \frac{\rho}{\varepsilon_0}
}
$$

### Data Presentation

| Component | Description                          | Status |
| :-------- | :----------------------------------- | :----- |
| Search    | Fuse.js powered full-site search     | Ready  |
| Comments  | Utterances integration               | Ready  |
| Analytics | Umami integration                    | Ready  |
| Dark Mode | Automatic system preference matching | Ready  |

---

## Media Showcase

### Image Lightbox
Click on any image to open it in a beautiful Fancybox lightbox.

![Demo Image](./test-image.png)

### Photo Rows
Use our `photo-row` shortcode to arrange multiple images horizontally.

{{< photo-row >}}
https://img.cicada000.work/BlogImage/2022/EVA-Telephone-Pole/ep1-3.png
https://img.cicada000.work/BlogImage/2022/EVA-Telephone-Pole/ep1-3.png
https://img.cicada000.work/BlogImage/2022/EVA-Telephone-Pole/ep1-3.png
{{< /photo-row >}}

---

# Final Thoughts

Thank you for exploring this showcase. We hope Seiheki provides the perfect canvas for your words. If you have any questions or feedback, feel free to visit our Github repository.

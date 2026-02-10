---
title: "Hello World：博客正式上线"
date: 2026-02-10
draft: false
description: "第一篇博客文章。"
summary: "Hugo + Blowfish 搭建个人技术博客。"
tags: ["Hugo", "博客", "Blowfish"]
categories: ["技术笔记"]
showHero: true
heroStyle: "background"
showTableOfContents: true
---

## 你好，世界！

这是我的第一篇博客文章。

### 测试 LaTeX

{{< katex >}}

行内公式：\(O(n \log n)\) 是归并排序的时间复杂度。

行间公式：

$$
\sum_{i=1}^{n} i = \frac{n(n+1)}{2}
$$

### 测试 Mermaid

{{< mermaid >}}
graph LR
    A[写 Markdown] --> B[Git Push] --> C[自动构建] --> D[全球可访问]
{{< /mermaid >}}

### 测试代码高亮

```go
func main() {
    fmt.Println("Hello, World! 🌱")
}
```

博客搭建完成 🎉

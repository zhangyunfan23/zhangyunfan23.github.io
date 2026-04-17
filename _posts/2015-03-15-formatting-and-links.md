---
layout: post
title: a post template
date: 2015-03-15 16:40:16
description: a minimal reference for how to write a new post
tags: formatting links
categories: sample-posts
---

This is a template post. Copy this file, rename it with today's date (`YYYY-MM-DD-slug.md`), and replace the content below.

## Headings and text

Standard Markdown works — **bold**, _italic_, [links](https://example.com), and `inline code`.

## Lists

- item one
- item two
  - nested item

## Check lists

- [x] done
- [ ] todo

## Code blocks

```python
def hello():
    print("hi")
```

## Blockquote

> Short quote goes here.
> — Author

## Images

Use the `figure.liquid` include to drop in images from `assets/img/`:

```liquid
{% raw %}{% include figure.liquid path="assets/img/example.jpg" class="img-fluid rounded z-depth-1" %}{% endraw %}
```

## Math

Inline math like $$E = mc^2$$ is enabled via MathJax (see `_config.yml`).

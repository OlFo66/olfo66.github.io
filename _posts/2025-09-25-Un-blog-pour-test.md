---
title: Adding Tags to Posts on GitHub Pages
description: How to use Jekyll tags on GitHub Pages blogs.
tags:
- Jekyll
- GitHub Pages
- Blog
---

## Titre


{% for tag in page.tags %}
    {{ tag }}
{% endfor %}

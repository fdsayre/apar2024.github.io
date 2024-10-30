# index.md
---
layout: default
title: Welcome to My Site
---

# Welcome

I'm [Your Name], and this is my personal website. Here you'll find my thoughts on technology, programming, and other interesting topics.

[Check out my blog](/blog) or [learn more about me](/about).

## Latest Posts
{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

# _posts/2024-10-30-my-first-post.md
---
layout: post
title: "My First Blog Post"
date: 2024-10-30
categories: blog
---

This is my first blog post using Jekyll. Here's how you can format content:

## Headers

### Smaller headers

**Bold text** and *italic text*

Lists:
- Item 1
- Item 2
  - Sub-item

Code blocks:
```python
def hello():
    print("Hello, World!")
```

[Links](https://example.com) are easy too!
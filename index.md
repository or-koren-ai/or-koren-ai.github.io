---
layout: professional
title: Home
---

# Welcome to My Professional Site

I'm a Data Science Team Lead with 11 years of experience in Data & ML, driving business value across diverse industries.

## Expertise

I specialize in machine learning, transformer models, causal inference, and data-driven optimization across multiple sectors including Ad-Tech, Retail, Energy, and Semiconductors.

## Recent Projects

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[Learn more about me](/about) 
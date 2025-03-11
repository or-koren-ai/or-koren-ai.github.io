---
layout: professional
title: Blog
permalink: /blog/
---

# Blog

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url | relative_url }})
<span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>

{{ post.excerpt }}

[Read more]({{ post.url | relative_url }})

---
{% endfor %} 
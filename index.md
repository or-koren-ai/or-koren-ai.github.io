---
layout: professional
title: Home
---

# Or Koren

I'm a Data Science Team Lead with 11 years of experience in Data & ML, driving business value across diverse industries.

## Areas of Expertise

<div class="expertise-grid">
  <div class="expertise-item">
    <h3>Machine Learning & AI</h3>
    <p>Extensive experience with LLMs, transformers, ML/DL across NLP, Computer Vision, and predictive modeling.</p>
  </div>
  
  <div class="expertise-item">
    <h3>Causal Inference</h3>
    <p>Applied causal inference methods to marketing campaigns and business optimization, generating millions in additional revenue.</p>
  </div>
  
  <div class="expertise-item">
    <h3>Data Engineering</h3>
    <p>Building robust data pipelines and architectures with Python, PySpark, SQL, and cloud technologies.</p>
  </div>
</div>

## Recent Projects

{% for post in site.posts limit:2 %}
<div class="section-card">
  <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
  {{ post.excerpt }}
  <a href="{{ post.url | relative_url }}">Read More →</a>
</div>
{% endfor %}

<a href="/projects" class="btn">View All Projects</a> 
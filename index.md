---
layout: professional
title: Home
---

<div class="section-card">
  <h1>Data Science & Machine Learning Expert</h1>
  <p>With 11 years of experience driving business value across diverse industries, I specialize in developing innovative data-driven solutions that deliver tangible results.</p>
  <a href="/about" class="btn">More About Me</a>
</div>

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
  <a href="{{ post.url | relative_url }}" class="btn">Read More</a>
</div>
{% endfor %}

<a href="/projects" class="btn">View All Projects</a> 
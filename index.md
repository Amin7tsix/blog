---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
---

<h1 style="text-align: right;">نوشته‌ها</h1>

<div class="post-list">
  {% for post in site.posts %}
    <div class="post-preview">
      {% if post.thumbnail %}
        <img src="{{ post.thumbnail | relative_url }}" alt="Thumbnail for {{ post.title }}">
      {% endif %}
      <div class="post-content">
        <h2 style="text-align: right;"><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
        <p style="text-align: right;">{{ post.excerpt | strip_html | truncatewords: 40 }}</p>
      </div>
    </div>
  {% endfor %}
</div>
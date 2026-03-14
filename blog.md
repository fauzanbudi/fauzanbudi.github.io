---
layout: default
title: Blog
permalink: /blog
---

<section>
  <h3>Blog</h3>

  <ul class="post-list">
    {% for post in site.posts %}
    <li>
      <h4><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h4>
      <p class="post-meta">{{ post.date | date: "%B %d, %Y" }}</p>
      {% if post.excerpt %}
      <p class="post-excerpt">{{ post.excerpt | strip_html | truncatewords: 40 }}</p>
      {% endif %}
    </li>
    {% endfor %}
    {% if site.posts.size == 0 %}
    <li><p>No posts yet. Check back soon!</p></li>
    {% endif %}
  </ul>
</section>

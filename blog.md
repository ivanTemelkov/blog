---
layout: default
title: Blog
permalink: /blog/
---

# Blog

{% if site.posts.size > 0 %}
  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y-%m-%d" }}</time>
        {% if post.tags.size > 0 %}
          <span class="post-tags">{{ post.tags | join: ", " }}</span>
        {% endif %}
      </li>
    {% endfor %}
  </ul>
{% else %}
  <p>No published posts yet.</p>
{% endif %}

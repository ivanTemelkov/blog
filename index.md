---
layout: default
title: Home
---

# Ivan Temelkov

Notes on software development, engineering practice, AI-assisted workflows, and lessons learned along the way.

## Recent posts

{% if site.posts.size > 0 %}
  <ul class="post-list">
    {% for post in site.posts limit:5 %}
      <li>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y-%m-%d" }}</time>
      </li>
    {% endfor %}
  </ul>
{% else %}
  <p>No published posts yet.</p>
{% endif %}

<p><a href="{{ '/blog/' | relative_url }}">View all posts</a></p>

---
layout: default
---

# Welcome 👋

This is my technical blog.


## 📝 Latest Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

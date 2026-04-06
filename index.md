---
layout: default
title: Home
---

# 👋 Jaime Marcelo

Technical Product Owner | Cloud | Data | Enterprise

---

## 📝 Latest Posts

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})

<span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>

---
{% endfor %}

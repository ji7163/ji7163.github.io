---
layout: page
permalink: /posts/
---

## 전체 목록

{% for post in site.posts %}

- {{ post.date | date: "%Y-%m-%d" }} - [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

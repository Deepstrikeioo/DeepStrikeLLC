---
layout: page
title: Articles
icon: fas fa-book-open
order: 4
---

## كل المقالات
اضغط على عنوان المقال للقراءة:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - <small>{{ post.date | date: "%Y-%m-%d" }}</small>
{% endfor %}

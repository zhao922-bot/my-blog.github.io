---
layout: home
title: 首页
---

欢迎来到我的数字花园！🌸

这里记录我的日常生活、技术思考和个人想法。

## 最新文章

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

---

感谢你的访问！😊

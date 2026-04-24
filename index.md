---
layout: default
title: 아재의 자동매매 다이어리
---

# 아재의 자동매매 다이어리
주식 자동매매를 함께 공부하는 공간입니다.

---

## 최신 글

{% for post in site.posts limit:3 %}
### [{{ post.title }}]({{ post.url }})
{{ post.date | date: "%Y년 %m월 %d일" }}

{{ post.excerpt }}

---
{% endfor %}

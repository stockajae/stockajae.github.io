---
layout: default
title: 아재의 자동매매 다이어리
---

# 아재의 자동매매 다이어리
주식 자동매매를 함께 공부하는 공간입니다.

---
## 카테고리
[📊 매매전략](/categories/매매전략) &nbsp;|&nbsp;
[📈 트레이드](/categories/트레이드) &nbsp;|&nbsp;
[☕ 일상](/categories/일상)

---

## 최신 글

{% for post in site.posts limit:3 %}
### [{{ post.title }}]({{ post.url }})
{{ post.date | date: "%Y년 %m월 %d일" }} &nbsp;|&nbsp; {{ post.categories | join: ", " }}

{{ post.excerpt }}

---
{% endfor %}

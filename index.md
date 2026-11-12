---
layout: default
title: ワシの買ったもの
---

「何を買ったか」ではなく「なぜ買う必要があったのか」から書く購入記録。

## 記事一覧

{% for p in site.pages %}{% if p.path contains 'posts/' %}
- [{{ p.title }}]({{ p.url | relative_url }})
{% endif %}{% endfor %}

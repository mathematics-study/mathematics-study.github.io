---
layout: default
---

<h2>
  프로그래머를 위한 확률과 통계
</h2>

{% for post in site.notes %}
  {% if post.url contains "/prob-stats/" %}
* [{{ post.title }}]({{ post.url }})
  {% endif %}
{% endfor %}
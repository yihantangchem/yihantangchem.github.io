---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% comment %} 
  自动抓取 _publications 文件夹下的所有文章
  reversed 表示按日期从新到旧排序
{% endcomment %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

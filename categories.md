---
layout: page
title: Categories
permalink: /Categories/
---
{% for category in site.categories %}
  * [{{ category | first }}]({{ site.baseurl }}/{{ category | first }})
{% endfor %}

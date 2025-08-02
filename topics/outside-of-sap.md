---
layout: category
title: Outside of SAP
data_file: outside-of-sap
---

{% assign topics = site.data[page.data_file] %}
<ul>
  {% for topic in topics %}
    <li><a href="/topics/{{ page.data_file }}/{{ topic.id }}.html">{{ topic.title }}</a></li>
  {% endfor %}
</ul>

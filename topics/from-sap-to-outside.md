---
layout: category
title: From SAP to the Outside
data_file: from-sap-to-outside
---

{% assign topics = site.data[page.data_file] %}
<ul>
  {% for topic in topics %}
    <li><a href="/topics/{{ page.data_file }}/{{ topic.id }}.html">{{ topic.title }}</a></li>
  {% endfor %}
</ul>

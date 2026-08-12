---
layout: default
title: Kariyer
permalink: /kariyer/
---

{% include signature.html %}
<h2>Kariyer</h2>

{% for item in site.data.kariyer.items %}
<div class="entry">
  <div class="entry-header">
    <span class="entry-title">{{ item.title }}</span>
    <span class="entry-date">{{ item.date }}</span>
  </div>
  <div class="entry-kurum">
    {{ item.kurum }}{% if item.in_progress %}<span class="tag">devam ediyor</span>{% endif %}
  </div>
  <p class="entry-body">{{ item.body }}</p>
</div>
{% endfor %}

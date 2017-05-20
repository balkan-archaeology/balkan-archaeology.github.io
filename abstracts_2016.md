---
layout: page
title: Abstracts from 2016
permalink: /abstracts-2016/
---
<div class="home">
  <ul class="post-list">
    {% for abstract in site.abstracts_2016 %}
    <li class="abstract-list-entry"
        onclick='window.open("{{ abstract.url }}","_self")'>
      <a href="{{ abstract.url }}" class="title-link">
        {{ abstract.title }} </a> <br>
      <b>{{ abstract.author }}</b>
      ({{ abstract.institution }}) <br>
      {% if abstract.keywords.size > 0 %}
      Keywords: <i>{{ abstract.keywords }}</i>
      {% endif %}
    </li>
    {% endfor %}
  </ul>
</div>

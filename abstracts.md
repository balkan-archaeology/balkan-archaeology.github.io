---
layout: page
title: Abstracts
permalink: /abstracts/
---
<div class="home">
  <ul class="post-list">
    {% for abstract in site.abstracts %}
      <li>
        <b>{{ abstract.author }}</b>,
        <i>{{ abstract.institution }}</i> -
        <a href="{{ abstract.url }}">{{ abstract.title }} </a>
      </li>
    {% endfor %}
  </ul>
</div>

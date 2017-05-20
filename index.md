---
layout: default
title: "Balkan Archaeology 2016"
---
# Welcome

The Department of Archaeology of Sofia University *St. Kliment
Ohridski* and the National Institute of Archaeology with Museum of the
Bulgarian Academy of Sciences jointly organize an international
doctoral student conference. It will take place in **Sofia, Bulgaria**
from **the 19th to the 21th of November 2017**. The conference topic
is **Balkan Archaeology**. Please see the [Call for
Papers](/call-for-papers/) and the [abstracts from the previous
edition](/abstracts-2016/).

All reports will be collected approximately three months after the
conference to be published in the [Bulgarian e-Journal of
Archaeology](http://be-ja.org/).

The conference in 2017 will be the fifth *Filov Symposium* and the
second with international participation.

# News

<div class="home">
  {% for post in site.posts %}
    <div>
      <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

      <h2> <a href="{{ post.url }}">{{ post.title }}</a> </h2>
      {{ post.content }}
      <br>
    </div>
  {% endfor %}
</div>

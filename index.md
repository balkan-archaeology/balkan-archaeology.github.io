---
layout: default
title: "Balkan Archaeology 2016"
---
# Welcome

The Department of Archaeology of Sofia University *St. Kliment
Ohridski* and the National Institute of Archaeology with Museum of the
Bulgarian Academy of Sciences jointly organize an international
doctoral student conference. It took place in **Sofia, Bulgaria** from
**the 17th to the 20th of November 2016**. The conference topic this
year was **Balkan Archaeology**. Please see the [Call for
Papers](/call-for-papers/).

All reports will be collected approximately three months after the
conference to be published in the [Bulgarian e-Journal of
Archaeology](http://be-ja.org/).

The conference in 2016 was the fourth *Filov Symposium* and the first
with international participation.

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

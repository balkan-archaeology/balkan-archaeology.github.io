---
layout: default
---
# Welcome

The Department of Archaeology of Sofia University *St. Kliment
Ohridski* and the National Institute of Archaeology with Museum of the
Bulgarian Academy of Sciences jointly organize an international
doctoral student conference. It will take place in **Sofia, Bulgaria**
from **the 17th to the 20th of November 2016**. The conference topic
this year is **Balkan Archaeology**. Please see the [Call for
Papers](/call-for-papers/).

The conference in 2016 is the fourth *Filov Symposium* and the first
with international participation.

To accommodate the significant number of participation requests, the
presentations will be in two parallel tracks -- *Prehistory* (from
the Paleolithic to the end of Bronze Age) and *Archaeology*.

# News

<div class="home">
  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2> <a href="{{ post.url }}">{{ post.title }}</a> </h2>
        {{ post.content }}
      </li>
    {% endfor %}
  </ul>
</div>

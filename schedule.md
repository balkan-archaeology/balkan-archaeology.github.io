---
layout: page
title: Programme
permalink: /programme/
---

{% assign slots = site.abstracts %}

{% for break in site.breaks %}
{% assign slots = slots | push: break %}
{% endfor %}

{% assign sorted_slots = slots | sort: 'timeslot' %}

<div class="schedule-date">Thursday, November 17</div>
<hr>

| 14.00 - 14.45 | Registration |
| 14.45 - 15.00 | Opening |

<div class="schedule-divider"><table><tr>
      <td>Afternoon session <br/> <em>Prehistory</em></td>
      <td><b>Sofia University, <br/> lecture hall 23</b></td>
      <td>Session chair: Rumyana Yordanova</td>
</tr></table></div>

<table class="schedule-table">
{% for slot in sorted_slots %}
{% if slot.session_id == "17a" %}
   <tr>
   <td>{{ slot.timeslot }}</td>
   <td>{{ slot.author }}</td>
   <td>{{ slot.title }}</td>
   </tr>
{% endif %}
{% endfor %}
</table>

<div class="schedule-date">Friday, November 18</div>
<hr>

<div class="schedule-divider"><table><tr>
      <td>Morning session <br/> <em>Prehistory</em></td>
      <td><b>Sofia University, <br/> lecture hall 41A</b></td>
      <td>Session chair: Denitsa Ilieva</td>
</tr></table></div>

<table class="schedule-table">
{% for slot in sorted_slots %}
{% if slot.session_id == "18mp" %}
   <tr>
   <td>{{ slot.timeslot }}</td>
   <td>{{ slot.author }}</td>
   <td>{{ slot.title }}</td>
   </tr>
{% endif %}
{% endfor %}
</table>

<div class="schedule-divider"><table><tr>
      <td>Morning session <br/> <em>Antiquity and Middle Ages</em></td>
      <td><b>Sofia University, <br/> lecture hall 23</b></td>
      <td>Session chair: Desislava Lyubenova</td>
</tr></table></div>

<table class="schedule-table">
{% for slot in sorted_slots %}
{% if slot.session_id == "18ma" %}
   <tr>
   <td>{{ slot.timeslot }}</td>
   <td>{{ slot.author }}</td>
   <td>{{ slot.title }}</td>
   </tr>
{% endif %}
{% endfor %}
</table>

<div class="schedule-divider"><table><tr>
      <td>Afternoon session <br/> <em>Prehistory</em></td>
      <td><b>Sofia University, <br/> lecture hall 41A</b></td>
      <td>Session chair: Zheni Vasileva</td>
</tr></table></div>

<table class="schedule-table">
{% for slot in sorted_slots %}
{% if slot.session_id == "18ap" %}
   <tr>
   <td>{{ slot.timeslot }}</td>
   <td>{{ slot.author }}</td>
   <td>{{ slot.title }}</td>
   </tr>
{% endif %}
{% endfor %}
</table>

<div class="schedule-divider"><table><tr>
      <td>Afternoon session <br/> <em>Antiquity and Middle Ages</em></td>
      <td><b>Sofia University, <br/> lecture hall 23</b></td>
      <td>Session chair: Vladislav Zhivkov</td>
</tr></table></div>

<table class="schedule-table">
{% for slot in sorted_slots %}
{% if slot.session_id == "18aa" %}
   <tr>
   <td>{{ slot.timeslot }}</td>
   <td>{{ slot.author }}</td>
   <td>{{ slot.title }}</td>
   </tr>
{% endif %}
{% endfor %}
</table>
<div class="schedule-date">Saturday, November 19</div>
<hr>

<div class="schedule-divider"><table><tr>
      <td>Morning session <br/> <em>Prehistory</em></td>
      <td><b>Sofia University, <br/> lecture hall 41A</b></td>
      <td>Session chair: Stanimir Parvanov</td>
</tr></table></div>

<table class="schedule-table">
{% for slot in sorted_slots %}
{% if slot.session_id == "19mp" %}
   <tr>
   <td>{{ slot.timeslot }}</td>
   <td>{{ slot.author }}</td>
   <td>{{ slot.title }}</td>
   </tr>
{% endif %}
{% endfor %}
</table>

<div class="schedule-divider"><table><tr>
      <td>Morning session <br/> <em>Antiquity and Middle Ages</em></td>
      <td><b>Sofia University, <br/> lecture hall 23</b></td>
      <td>Session chair: Georgi Sengalevich</td>
</tr></table></div>

<table class="schedule-table">
{% for slot in sorted_slots %}
{% if slot.session_id == "19ma" %}
   <tr>
   <td>{{ slot.timeslot }}</td>
   <td>{{ slot.author }}</td>
   <td>{{ slot.title }}</td>
   </tr>
{% endif %}
{% endfor %}
</table>

<div class="schedule-divider"><table><tr>
      <td>Afternoon session <br/> <em>Prehistory</em></td>
      <td><b>Sofia University, <br/> lecture hall 41A</b></td>
      <td>Session chair: Nikolina Nikolova</td>
</tr></table></div>

<table class="schedule-table">
{% for slot in sorted_slots %}
{% if slot.session_id == "19ap" %}
   <tr>
   <td>{{ slot.timeslot }}</td>
   <td>{{ slot.author | remove: "†" | remove: "‡"}}</td>
   <td>{{ slot.title }}</td>
   </tr>
{% endif %}
{% endfor %}
</table>

<div class="schedule-divider"><table><tr>
      <td>Afternoon session <br/> <em>Antiquity and Middle Ages</em></td>
      <td><b>Sofia University, <br/> lecture hall 23</b></td>
      <td>Session chair: Vladimir Staykov</td>
</tr></table></div>

<table class="schedule-table">
{% for slot in sorted_slots %}
{% if slot.session_id == "19aa" %}
   <tr>
   <td>{{ slot.timeslot }}</td>
   <td>{{ slot.author }}</td>
   <td>{{ slot.title }}</td>
   </tr>
{% endif %}
{% endfor %}
</table>

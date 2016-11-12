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

<table class="schedule-contents-table">
<tr><td>
Jump to:
</td></tr>
<tr><td class="schedule-contents-table-date">
  <a href="#17-november">Thursday, November 17</a>
</td></tr>
<tr><td>
  <a href="#17a">Afternoon session <em>Prehistory</em></a>
</td></tr>
<tr><td class="schedule-contents-table-date">
  <a href="#18-november">Friday, November 18</a> <br/>
</td></tr>
<tr>
  <td>
    <a href="#18mp">Morning session <em>Prehistory</em></a> <br/>
    <a href="#18ap">Afternoon session <em>Prehistory</em></a>
  </td>
  <td>
    <a href="#18ma">Morning session <em>Antiquity and Middle Ages</em></a> <br/>
    <a href="#18aa">Afternoon session <em>Antiquity and Middle Ages</em></a>
  </td>
</tr>
<tr><td class="schedule-contents-table-date">
    <a href="#19-november">Saturday, November 19</a>
</td></tr>
<tr>
  <td>
    <a href="#19mp">Morning session <em>Prehistory</em></a> <br/>
    <a href="#19ap">Afternoon session <em>Prehistory</em></a>
  </td>
  <td>
    <a href="#19ma">Morning session <em>Antiquity and Middle Ages</em></a> <br/>
    <a href="#19aa">Afternoon session <em>Antiquity and Middle Ages</em></a>
  </td>
</tr>
</table>

<div class="schedule-date" id="17-november">Thursday, November 17</div>
<hr>

| 14.00 - 14.45 | Registration |
| 14.45 - 15.00 | Opening |

<div class="schedule-divider" id="17a"><table><tr>
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
   <td><a href="{{ slot.url }}">{{ slot.title }}</a></td>
   </tr>
{% endif %}
{% endfor %}
</table>

<div class="schedule-date" id="18-november">Friday, November 18</div>
<hr>

<div class="schedule-divider" id="18mp"><table><tr>
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
   <td><a href="{{ slot.url }}">{{ slot.title }}</a></td>
   </tr>
{% endif %}
{% endfor %}
</table>

<div class="schedule-divider" id="18ma"><table><tr>
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
   <td><a href="{{ slot.url }}">{{ slot.title }}</a></td>
   </tr>
{% endif %}
{% endfor %}
</table>

<div class="schedule-break"><hr/><table><tr>
     <td>12.15 - 14.15</td>
     <td><em>Lunch break</em></td>
</tr></table><hr/></div>

<div class="schedule-divider" id="18ap"><table><tr>
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
   <td><a href="{{ slot.url }}">{{ slot.title }}</a></td>
   </tr>
{% endif %}
{% endfor %}
</table>

<div class="schedule-divider" id="18aa"><table><tr>
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
   <td><a href="{{ slot.url }}">{{ slot.title }}</a></td>
   </tr>
{% endif %}
{% endfor %}
</table>
<div class="schedule-date" id="19-november">Saturday, November 19</div>
<hr>

<div class="schedule-divider" id="19mp"><table><tr>
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
   <td><a href="{{ slot.url }}">{{ slot.title }}</a></td>
   </tr>
{% endif %}
{% endfor %}
</table>

<div class="schedule-divider" id="19ma"><table><tr>
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
   <td><a href="{{ slot.url }}">{{ slot.title }}</a></td>
   </tr>
{% endif %}
{% endfor %}
</table>

<div class="schedule-break"><hr/><table><tr>
     <td>12.15 - 14.15</td>
     <td><em>Lunch break</em></td>
</tr></table><hr/></div>


<div class="schedule-divider" id="19ap"><table><tr>
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
   <td><a href="{{ slot.url }}">{{ slot.title }}</a></td>
   </tr>
{% endif %}
{% endfor %}
</table>

<div class="schedule-divider" id="19aa"><table><tr>
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
   <td><a href="{{ slot.url }}">{{ slot.title }}</a></td>
   </tr>
{% endif %}
{% endfor %}
</table>

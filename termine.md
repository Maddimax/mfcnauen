---
layout: page
title: Termine
permalink: /termine/
---


<ul class="event-list">
{% for termin in site.data.termine %}

{% if termin.dtend > site.time %}
<li class="future-event">
{% else %}
<li class="past-event">
{% endif %}
<span class="event-date">{{ termin.human_readable_date }}: </span>{{ termin.title }}<br>
<small>
    <a href="{{ termin.location_url | absolute_url }}">{{termin.location}}</a>
</small>
</li>
{% endfor %}
</ul>

<small><a href="/mfc-nauen-termine.ics">Termine abonnieren</a></small>

---
layout: page
title: Termine
permalink: /termine/
---

{% for termin in site.data.termine %}
- **{{ termin.human_readable_date }}:** {{ termin.title }}<br><small>[{{termin.location}}]({{ termin.location_url | absolute_url }}) 
{% endfor %}

<small>Als iCalendar abonnieren: <a href="/mfc-nauen-termine.ics">mfc-nauen-termine.ics</a></small>

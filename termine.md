---
layout: page
title: Termine
permalink: /termine/
---

{% for termin in site.data.termine %}
- **{{ termin.human_readable_date }}:** {{ termin.title }}<br><small>[{{termin.location}}]({{ termin.location_url | absolute_url }}) 
{% endfor %}

<small><a href="/mfc-nauen-termine.ics">Termine abonnieren</a></small>

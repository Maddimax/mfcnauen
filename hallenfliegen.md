---
layout: page
title: Hallenfliegen
permalink: /hallenfliegen/
---

Unser Hallenfliegen findet dieses Jahr wieder an den folgenden Samstagen von 14:00 bis 17:00 in der
[Sporthalle des Goethe Gymnasium Nauen](https://maps.app.goo.gl/Apfc6FYo5ofCXaW4A){:target="_blank"}
statt.

Der Unkostenbeitrag beträgt für Piloten ab 18 Jahren 3€ pro Veranstaltung.

<ul class="event-list">
{% for termin in site.data.hallenfliegen %}

{% if termin.date > site.time %}
<li class="future-event">
{% else %}
<li class="past-event">
{% endif %}

    {{ termin.date | date: "%d.%m.%Y" }}<br>
</li>
{% endfor %}

</ul>

<small><a href="/hallenfliegen.ics">Termine abonnieren</a></small>

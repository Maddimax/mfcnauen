---
layout: page
title: Hallenfliegen
permalink: /hallenfliegen/
---

Unser Hallenfliegen findet dieses Jahr wieder an den folgenden Samstagenvon 13:30 bis 18:00 in der
[Sporthalle des Goethe Gymnasium Nauen](https://maps.app.goo.gl/Apfc6FYo5ofCXaW4A){:target="_blank"}
statt:


{% for termin in site.data.hallenfliegen %}
* {{ termin.date }}{% endfor %}

<small><a href="/hallenfliegen.ics">Termine abonnieren</a></small>

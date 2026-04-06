---
title: "Organisers"
layout: single
sidebar: null
---

{% for organizer in site.data.autoai_fm.organizers %}
- **{{ organizer.name }}**, {{ organizer.affiliation }} ([Website]({{ organizer.website }}){:target="_blank"})
{% endfor %}

Contact: [autoaifm@aim.rwth-aachen.de](mailto:autoaifm@aim.rwth-aachen.de)

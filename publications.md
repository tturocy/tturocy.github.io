---
layout: page
title: Publications
---

{% for section in site.data.publications.sections %}
### {{ section.title }}

{% for item in section.items %}
{% include publication.html item=item %}
{% endfor %}

{% endfor %}

---
layout: page
title: publications
nav: true
nav_order: 1
---

<div>

{% for entry in site.data.pubs.papers %}
    {% include newpub.liquid %}
{% endfor %}

<h3> reports and unpublished work </h3>

{% for entry in site.data.pubs.reports %}
    {% include newpub.liquid %}
{% endfor %}
</div>

---
layout: page
title: teaching
permalink: /teaching/
---

Here are some artifacts I'm proud of from prior teaching opportunities.

<div class="mb-1 mt-5">

<!--h3> in-class activities </h3> 

<div>

I've worked on adding active learning components to classes I've taught, mostly
through worksheets.

</div>

</div>

<div class="mb-1 mt-5"-->

<h3> guest lectures </h3>

{% for project in site.projects %}

{% if project.category == 'guest' %}
    {% include card.html %}

{% endif %}

{% endfor %}

</div>
<div class="mb-1 mt-5">

<h3> miscellaneous </h3>

{% for project in site.projects %}

{% if project.category == 'misc' %}
    {% include card.html %}

{% endif %}

{% endfor %}

</div>

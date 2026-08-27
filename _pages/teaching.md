---
layout: page
title: teaching
permalink: /teaching/
---

In Spring 2026, I taught CICS 160: Introduction to Object-Oriented Programming
(UMass).

In Fall 2025, I taught COMSC 334: Artificial Intelligence (Mount Holyoke
College). <br>

Detailed teaching experience, including TAships and guest lectures, is listed
in my [CV]({{ "/cv/" | relative_url }}). Below, I've included some artifacts
I'm proud of from various teaching opportunities. 

<div class="mb-1 mt-5">

<h3> guest lectures </h3>


<div class="row">
{% for project in site.projects %}

{% if project.category == 'guest' %}
    {% include card.html %}

{% endif %}

{% endfor %}

</div>

<!-- 
{% for project in site.projects %}

{% if project.category == 'guest' %}
    {% include card.html %}

{% endif %}

{% endfor %}
 -->
</div>
<div class="mb-1 mt-5">

<h3> miscellaneous </h3>

{% for project in site.projects %}

{% if project.category == 'misc' %}
    {% include card.html %}

{% endif %}

{% endfor %}

</div>

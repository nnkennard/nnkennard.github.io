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
in my [CV]({{ "/cv/" | relative_url }}).

Below, I've shared some artifacts I'm proud of from various teaching opportunities. 

{% assign sorted_projects = site.projects | sort: 'year' | reverse%}
{% for cat in site.data.settings.categories %}

<div class="row mt-5">
    <h2> {{cat.title}} </h2>
    {% for project in sorted_projects %}
        {% if project.category == cat.key %}
            {% include card.html %}
        {% endif %}
    {% endfor %}
</div>

{% endfor %}

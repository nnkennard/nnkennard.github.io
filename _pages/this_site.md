---
layout: page
title: this website
permalink: /this_site/
---


This website borrows elements from:
  {% for cred in site.data.settings.credits %}
    <a style="color:#404040;" href="{{ cred.link }}">{{ cred.name }}</a>
    {% unless forloop.last %}
    ·
    {% endunless %}
  {% endfor %}

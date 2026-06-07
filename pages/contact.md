---
layout: page
title: "contact"
---

(and other links)
  <div class="col-md-12 text-center mt-3 mb-3">

    
      {% for item in site.data.settings.social %}
        <a href="{{ item.link }}"> {{ item.name }}</a>
        {% unless forloop.last %}
        |
        {% endunless %}

      {% endfor %}
  </div>


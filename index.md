<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
<h2> Reports and unpublished work </h2>
{% for post in site.reports reversed %}
  {% include archive-single.html %}
{% endfor %}

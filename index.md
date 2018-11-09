I'm a PhD student in Computer Science at U Mass Amherst, advised by [Prof. Andrew McCallum](https://people.cs.umass.edu/~mccallum/). Previously, I completed my MS in Computer Science at Stanford, advised by [Prof. Chris Manning](https://nlp.stanford.edu/~manning/), and compeleted my Bachelor's thesis at the Institute for Natural Language Processing in Stuttgart, supervised by [PD Dr. Sabine Schulte im Walde](http://www.schulteimwalde.de/).

Most recently, I worked on deep learning for dialogue at Google Research. Before
that, I  trying to encode lexical relations in vector
representations of words, especially hypernymy (my favorite!)

Currently, I'm working aligning biomedical ontologies (more hypernyms! :-)), and
over the rest of my PhD look forward to thinking more deeply about 

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
<h2> Reports and unpublished work </h2>
{% for post in site.reports reversed %}
  {% include archive-single.html %}
{% endfor %}
 

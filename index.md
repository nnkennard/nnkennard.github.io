I'm a PhD student in Computer Science at UMass Amherst, advised by [Prof. Andrew McCallum](https://people.cs.umass.edu/~mccallum/). Previously, I completed my MS in Computer Science at Stanford, advised by [Prof. Chris Manning](https://nlp.stanford.edu/~manning/), and compeleted my Bachelor's thesis at the Institute for Natural Language Processing in Stuttgart, supervised by [PD Dr. Sabine Schulte im Walde](http://www.schulteimwalde.de/).

Most recently, I worked on deep learning for dialogue at Google Research. Before
that, I worked on learning word vectors that encoded challenging lexical relations, especially hypernymy, and then interrogated what they actually did encode with [VecEval](http://www.veceval.com).
 
Currently, I'm making use of my familiarity with hypernyms to align biolemdical ontologies. Over the rest of my PhD I look forward to thinking more deeply about compositional representations and developing representations whose geometric properties better reflect the semantics of human language.

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
<h2> Reports and unpublished work </h2>
{% for post in site.reports reversed %}
  {% include archive-single.html %}
{% endfor %}
 

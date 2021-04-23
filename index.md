I'm a PhD student in Computer Science at UMass Amherst, advised by [Prof. Andrew McCallum](https://people.cs.umass.edu/~mccallum/). Previously, I completed my MS in Computer Science at Stanford, advised by [Prof. Chris Manning](https://nlp.stanford.edu/~manning/), and completed my Bachelor's thesis at the Institute for Natural Language Processing in Stuttgart, supervised by [PD Dr. Sabine Schulte im Walde](http://www.schulteimwalde.de/).

Most recently, I worked on deep learning for dialogue at Google Research. Before
that, I worked on learning word vectors that encoded challenging lexical relations, especially hypernymy, and then interrogated what they actually did encode with [VecEval](http://www.veceval.com).

Currently, I'm working on problems in discourse structure at the document level. I'm particularly interested in understanding the interactions that take place during peer review through the lens of discourse. My hope is that this work will contribute to making peer review more transparent and equitable.


Here is my [resume](http://nnkennard.github.io/files/Kennard_Resume_Nov2020.pdf).


<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
<h2> Reports and unpublished work </h2>
{% for post in site.reports reversed %}
  {% include archive-single.html %}
{% endfor %}
 

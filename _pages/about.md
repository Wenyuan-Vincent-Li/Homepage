---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a research scientist of Facebook working on machine learning and deep learning with applications to Facebook products.
I complete my Ph.D in the [Department of Electrical and Computer Engineering](https://www.ee.ucla.edu/), 
[Computational Diagnostics Lab](https://www.uclahealth.org/urology/iuo/arnold-lab), and [Medical Image Informatics Lab](https://www.mii.ucla.edu/)
at [University of California, Los Angeles](http://www.ucla.edu/) in September 2020. I was advised by [Prof. Corey Arnold](https://www.mii.ucla.edu/people/cwarnold/)
and co-advised by [Prof. Greg Pottie](http://www.seas.ucla.edu/~pottie/). My research interests lie in the
 __real-life application of machine learning and deep learning__.

## Recent News
{% include base_path %}
{% for post in site.news reversed %}
  {% include front-recent-news.html %}
  {% if forloop.index == 3 %}
    {% break %}
  {% endif %}
{% endfor %}
[Read more news]({{site.url}}/news)
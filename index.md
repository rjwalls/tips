---
layout: default_minimal
title: Random Tips 
---

This page is just a collection of random commands and such that
[myself](http://www.cse.psu.edu/~rjwalls/) (or
others) have found useful. If you'd like to contribute, then send me a pull
request on [Github](https://github.com/rjwalls/tips).

<ul class="news list-unstyled">
{% for post in site.posts %}
  <li>
    <h3>{{ post.title }}</h3>
    {{ post.content | strip_html | truncatewords: 40}}
    <a href="{{ post.url }}">Read more.</a>
  </li>
{% endfor %}
</ul>



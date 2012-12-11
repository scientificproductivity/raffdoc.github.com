---
layout: default
title: raffdoc.github.com
tagline: Reproducible research in biomedical sciences
---
{% include JB/setup %}
### Latest Blog Post ###
{% for post in site.posts limit:3 %}
  <p>
    <strong><a href="{{ post.url }}">{{ post.title | xml_escape }}</a></strong>
    <span>
    	<em><time datetime="{{ post.date | date: "%Y-%m-%d" }}">
    		{{ post.date | date: "%B %d, %Y" }}
    	</time></em>
    </span>
  <br />{{ post.content | split:"<!--more-->" | strip_html | truncatewords: 50 }} <a href="{{ post.url }}">continue reading...</a>
  </p>
{% endfor %}

[More blog posts](/blog.html)
    
## More to Come



## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.



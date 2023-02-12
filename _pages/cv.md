---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Computing Science, Simon Fraser University, 2016
* B.S. in Statistics, Sun Yat-Sen University, 2013

Work experience
======
* Fall 2019: Applied Scientist
  * AWS AI Lab, Shanghai, China

* Spring 2018: Applied Scientist
  * AWS, Palo Alto, USA

* Fall 2016: Software Engineer
  * Fortinet, Vancouver, Canada

* Fall 2015: Research Intern
  * ContextualGenomics, Vancouver, Canada
  
Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

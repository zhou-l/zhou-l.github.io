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
* Ph.D in Computing, University of Utah, 2014

Work experience
======
* 2020 -- Now: Assistant Professor
  * NIHDS, Peking University
  
* 2019 -- 2020: Research Associate
  * SCI Institute, University of Utah

* 2015 -- 2018: Research Associate
  * VISUS, University of Stuttgart

* 2014 -- 2015: Postdoc Researcher
  * SCI Institute, University of Utah
  

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  


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
* Ph.D in Industrial and Systems Engineering, University of Southern California, 2030 (expected)
* B.S. in Computer Science, B.S. in Operations Research and Information Engineering, Cornell University, 2025

Research experience
======
<ul>{% for post in site.research reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* Programming Languages and Tools
  * Python, Java, MATLAB, C, SQL
* Machine Learning Packages
  * PyTorch, Jax, Numpy, Pandas
* Optimization and Machine Learning Theory

Service and leadership
======
* Volunteer at Los Angeles Animal Services
* [Leader of Cat co.](/mycats/)

<!-- Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

   -->
  




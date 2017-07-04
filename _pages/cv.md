---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /wordpress/cv/
---

{% include base_path %}

Education
======
* Bachelors in Statistics, Chemical Biology, Computer Science and Applied Math, Highest Honor, UC Berkeley, August2013 - August 2017

Research experience
======
* Summer 2015: Research Assistant
  * UC Berkeley
  * Duties included: 
  * Supervisor: 

* Fall 2015: Research Assistant
  * UC Berkeley
  * Duties included: 
  * Supervisor: 
  
* Fall 2015: Research Assistant
  * UC Berkeley
  * Duties included: 
  * Supervisor: 
  
* Fall 2015: Research Assistant
  * UC Berkeley
  * Duties included: 
  * Supervisor: 

Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  {% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}

Presentations
======
  {% for post in site.talks %}
    {% unless post.talk_type == "Conference proceedings talk" %}
      {% include archive-single-talk-cv.html %}
    {% endunless %}
  {% endfor %}

Teaching
======
  {% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}

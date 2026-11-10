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
* Ph.D in Version Control Theory, Example University, 2018 (expected)
* M.S. in Jekyll, Example University, 2014

Work experience
======
* Spring 2024: Research Assistant
  * Example University
  * Duties included: Maintaining the starter theme

Skills
======
* Skill 1
* Skill 2

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

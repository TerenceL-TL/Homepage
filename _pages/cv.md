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
=========

* B.Eng. in Computer Science, Harbin Institute of Technology, Shenzhen, 2026 (expected)

Publications
============
{% for post in site.publications reversed %} {% include archive-single-cv.html %} {% endfor %}

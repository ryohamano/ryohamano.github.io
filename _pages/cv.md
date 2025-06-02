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
* Bachelor of Science, Waseda University
  * April 2020 - March 2024
  * Director: Prof. Mochizuki
  * Thesis: 近藤格子磁性体における光誘起磁気転移の理論研究　( Theoretical study of the photo-induced magnetic phase transition in the Kondo lattice magnet )

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

Publications
======
  <ul>{% for post in site.publication_md_files reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talk_md_files reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
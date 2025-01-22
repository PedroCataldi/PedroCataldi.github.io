---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---


{% include base_path %}
<p align="left">
<img src="/images/Pedro_Cataldi_CV__english_1.png"  width="700" height="200">
</p>

<p align="left">
<img src="/images/Pedro_Cataldi_CV__english_2.png"  width="700" height="200">
</p>

<p align="left">
<img src="/images/Pedro_Cataldi_CV__english_3.png"  width="700" height="100">
</p>


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
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
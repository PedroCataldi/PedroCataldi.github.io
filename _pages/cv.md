---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-images">
  <img src="/images/Pedro_Cataldi_CV_0.png" alt="CV page 1">
  <img src="/images/Pedro_Cataldi_CV_1.png" alt="CV page 2">
  <img src="/images/Pedro_Cataldi_CV_2.png" alt="CV page 3">
  <img src="/images/Pedro_Cataldi_CV_3.png" alt="CV page 4">
  <img src="/images/Pedro_Cataldi_CV_4.png" alt="CV page 5">
  <img src="/images/Pedro_Cataldi_CV_5.png" alt="CV page 6">
  <img src="/images/Pedro_Cataldi_CV_6.png" alt="CV page 7">
</div>

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
Proceedings
======
  <ul>{% for post in site.proceedings %}
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
  
---
layout: archive
title: "Academic Services"
permalink: /services/
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Journal Reviewer

* IEEE Transactions on Automatic Control (TAC)
* Automatica
* Nonlinear Analysis: Hybrid Systems (NAHS) 
* IEEE Transactions on Control of Network Systems (TCNS) 
* ACM Transactions on Embedded Computing Systems (TECS) 
* European Journal of Control (EJC) 
* Journal of the Franklin Institute (JFI) 
* IEEE Control Systems Letters (L-CSS) 
* IEEE Open Journal of Control Systems (OJCSYS)

## Conference Reviewer

* IEEE Conference on Decision and Control (CDC) 
* American Control Conference (ACC)
* European Control Conference (ECC) 
* IFAC Conference on Analysis and Design of Hybrid Systems (ADHS)
* IEEE Chinese Control Conference (CCC)

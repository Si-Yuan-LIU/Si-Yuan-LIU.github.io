---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

* **October 2022**: I will be joining the Division of Decision and Control Systems at KTH Royal Institute of Technology as a Postdoc Researcher in January 2023.
* **September 2022**: I successfully defended my PhD.
* **May 2022**: I received a two-year Postdoc Fellowship suported by Digital Futures in Sweden.
* **April 2022**: Our vision paper entitled "Secure-by-construction synthesis of cyber-physical systems" got appeared at Annual Reviews in Control.

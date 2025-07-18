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
* **July 2025**: I will be joining the Control Systems (CS) Group at Eindhoven University of Technology (TU/e) as an Assistant Professor, starting September 1st, 2025. 
* **December 2024**: I am awarded the Wallenberg-NTU Presidential Postdoctoral Fellowship (5/~1k applicants per year).
* **December 2024**: I gave a guest lecture for the graduate course _Multi-Agent Systems_ at Osaka Metropolitan University.
* **June 2024**: Check out our ECC24 workshop on [Task and Motion Coordination under Geometric, Dynamic and Temporal Constraints (TMC+X)](https://tmc-x.github.io/). 
* **April 2024**: I received the Digital Futures Best Poster Presentation Award during the Digital Futures Open Research Days event. 
* **December 2022**: I gave a guest lecture for the graduate course _Control Principles for Engineered Systems_ at Eindhoven University of Technology (TU/e).
* **October 2022**: I will be joining the Division of Decision and Control Systems at KTH Royal Institute of Technology as a Postdoc Researcher in January 2023.
* **September 2022**: I successfully defended my PhD.
* **May 2022**: I received a two-year Postdoc Fellowship suported by Digital Futures in Sweden.
* **April 2022**: Our vision paper entitled "Secure-by-construction synthesis of cyber-physical systems" got appeared at Annual Reviews in Control.

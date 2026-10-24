---
layout: archive
title: "People"
permalink: /people/
author_profile: true
---

<div class="people-grid">
  {% for person in site.data.people %}
  <article class="people-member">
    {% if person.image %}
    <img class="people-member__photo" src="{{ person.image | relative_url }}" alt="{{ person.name | escape }}">
    {% else %}
    <div class="people-member__placeholder" aria-hidden="true">
      <i class="fas fa-user"></i>
    </div>
    {% endif %}
    <h2 class="people-member__name">
      {% if person.website %}<a href="{{ person.website | escape }}">{{ person.name }}</a>{% else %}{{ person.name }}{% endif %}
    </h2>
    <div class="people-member__details">
      {% if person.role %}<p>{{ person.role }}</p>{% endif %}
      {% if person.description %}<p>{{ person.description }}</p>{% endif %}
    </div>
  </article>
  {% endfor %}
</div>

## Master Students

| Name | Affiliation | Co-supervised with | Year |
| --- | --- | --- | --- |
| Andras | TU/e | — | 2026–2027 |
| Vyshnav | TU/e | Siep and Jake | 2026 |
| Xinyuan | TU/e | Sofie | 2026 |
| MSc. Benjamin Brandin | KTH | — | 2024 |
| MSc. Georgios Mitsos | KTH | — | 2025 |
| MSc. Zelin Yu | KTH & Scania | — | 2024 |

## Bachelor Students

| Name | Affiliation | Co-supervised with | Year |
| --- | --- | --- | --- |
| Mohammad Shouly | TU/e | Wefabricate | 2026 |

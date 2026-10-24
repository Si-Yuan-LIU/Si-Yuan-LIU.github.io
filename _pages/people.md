---
layout: archive
title: "People"
permalink: /people/
author_profile: true
---

## PhD Students

<div class="people-grid">
  {% for person in site.data.people %}
  <article class="people-member">
    <div class="people-member__avatar">
      {% if person.image %}
      <img class="people-member__photo" src="{{ person.image | relative_url }}" alt="{{ person.name | escape }}" width="112" height="112" loading="lazy">
      {% else %}
      <div class="people-member__placeholder" aria-hidden="true">
        <i class="fas fa-user"></i>
      </div>
      {% endif %}
    </div>
    <h3 class="people-member__name">
      {% if person.website %}<a href="{{ person.website | escape }}">{{ person.name }}</a>{% else %}{{ person.name }}{% endif %}
    </h3>
    {% if person.role or person.description %}
    <div class="people-member__details">
      {% if person.role %}<p>{{ person.role }}</p>{% endif %}
      {% if person.description %}<p>{{ person.description }}</p>{% endif %}
    </div>
    {% endif %}
  </article>
  {% endfor %}
</div>

## Master Students

| Name | Affiliation | Co-supervised with | Year |
| --- | --- | --- | --- |
| András Szabó | TU/e | — | 2026–2027 |
| MSc. Vyshnav Sunil | TU/e | Siep and Jake | 2026 |
| MSc. Xinyuan Qiu | TU/e | Sofie | 2026 |
| MSc. Benjamin Brandin | KTH | — | 2024 |
| MSc. Georgios Mitsos | KTH | — | 2025 |
| MSc. Zelin Yu | KTH | Scania | 2024 |

## Bachelor Students

| Name | Affiliation | Co-supervised with | Year |
| --- | --- | --- | --- |
| Mohammad Shouly | TU/e | Wefabricate | 2026 |

---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

## Teaching philosophy

My teaching focuses on learning-by-doing, frequent feedback, and inclusive participation.
{: .notice }

I design assignments that mirror real research workflows: reading, critique, iteration, and presentation.
{: .notice--primary }

## Mentoring

I mentor students with a “scaffold then fade” approach: structure early, independence later.
{: .notice--info }

---

## Courses

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}

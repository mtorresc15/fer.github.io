---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Classical-Quantum Physics

This work provides an overview of my research in undergraduate in the classical to quantum division using collapse model interpretetion.

* ** Torres, F.**, Modak S., Aranda A. (2023). "New insights on the quantum-classical division in light of Collapse Models." <i> Springer: Foundations on Physics. </i> Full text available at .



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---
layout: page
title: "Projetos"
permalink: /projetos/
---

Conheça os projetos vinculados ao Observatório Oceanográfico da UFF.

<ul>
  {% for projeto in site.projetos %}
    <li>
      <a href="{{ projeto.url | relative_url }}">{{ projeto.title }}</a>
    </li>
  {% endfor %}
</ul>

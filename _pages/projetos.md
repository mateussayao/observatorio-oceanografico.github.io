---
layout: page
title: "Projetos"
permalink: /projetos/
---

<div class="equipe-grid">
  {% for projeto in site.projetos %}
    <div class="card">
      {% if projeto.image %}
        <img src="{{ projeto.image | relative_url }}" alt="Imagem de {{ projeto.title }}">
      {% endif %}
      <h3><a href="{{ projeto.url | relative_url }}">{{ projeto.title }}</a></h3>
      <p>{{ projeto.excerpt | markdownify }}</p>
    </div>
  {% endfor %}
</div>



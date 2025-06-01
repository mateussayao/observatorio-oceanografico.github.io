---
layout: page
title: "Ensino"
permalink: /ensino/
---

<div class="equipe-grid">
  {% for disciplina in site.ensino %}
    <div class="card">
      {% if disciplina.image %}
        <img src="{{ disciplina.image | relative_url }}" alt="Imagem de {{ disciplina.title }}">
      {% endif %}
      <h3><a href="{{ disciplina.url | relative_url }}">{{ disciplina.title }}</a></h3>
      <p>{{ disciplina.excerpt | markdownify }}</p>
    </div>
  {% endfor %}
</div>


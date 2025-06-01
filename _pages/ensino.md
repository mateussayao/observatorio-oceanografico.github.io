---
layout: page
title: "Ensino"
permalink: /ensino/
---

<div class="equipe-grid">
  {% for disciplina in site.ensino %}
    <div class="card card-ensino">
      {% if disciplina.image %}
        <img class="img-ensino" src="{{ disciplina.image | relative_url }}" alt="{{ disciplina.title }}">
      {% endif %}
      <h3><a href="{{ disciplina.url | relative_url }}">{{ disciplina.title }}</a></h3>
      {% if disciplina.nivel %}
        <p style="font-size: 0.9rem; color: #555; margin-top: 0.25rem;">{{ disciplina.nivel }}</p>
      {% endif %}
    </div>
  {% endfor %}
</div>



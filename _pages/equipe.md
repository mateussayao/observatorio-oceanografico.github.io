---
layout: default
title: "Equipe"
permalink: /equipe/
sidebar:
  nav: equipe
---

Conheça os membros da nossa equipe.

<div class="equipe-grid">
  {% for member in site.equipe %}
  <div class="card">
    <a href="{{ member.url }}">
      <img src="{{ member.avatar }}" alt="Foto de {{ member.title }}">
      <h3>{{ member.title }}</h3>
    </a>
    {% if member.profile.location %}
    <p>{{ member.profile.location }}</p>
    {% endif %}
  </div>
  {% endfor %}
</div>

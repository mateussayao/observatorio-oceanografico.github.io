---
layout: single
title: "Equipe"
permalink: /equipe/
sidebar:
  nav: equipe
---

Conheça os membros da nossa equipe.

{% for member in site.equipe %}
### [{{ member.title }}]({{ member.url }})

![Foto de {{ member.title }}]({{ member.avatar }}){: .profilepic }

{{ member.excerpt | markdownify }}
<hr>
{% endfor %}
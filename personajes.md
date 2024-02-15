---
title: personajes

---


{% for personaje in site.data.personajes %}
  ## {{ personaje.nombre }} - {{ personaje.nivel }}
{% endfor %}
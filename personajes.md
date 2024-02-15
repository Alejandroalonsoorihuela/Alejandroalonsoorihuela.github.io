---
title: members

---

# Members


{% for member in site.members %}
  ## {{ member.name }} - {{ member.position }}
  [ver]({{ member.url }}) 
  {{ member.content | markdownify }}
{% endfor %}


{% for personaje in site.data.personajes %}
  ## {{ personaje.nombre }} - {{ personaje.edad }}
{% endfor %}
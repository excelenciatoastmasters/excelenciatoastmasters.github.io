---
layout: single
title: Contacto
---

Si quieres información o venir como invitado a una de nuestras reuniones a probar, contacta con nosotros.
Puedes asistir como invitado a varias sesiones del club hasta que estés seguro de si el metodo de aprendizaje del club encaja contigo.

## Datos de Contacto
<ul class="social-icons">
  {% if site.footer.links %}
    {% for link in site.footer.links %}
       {% if link.label and link.url %}
         <li><a href="{{ link.url }}" rel="nofollow noopener noreferrer"><i class="{{ link.icon | default: 'fas fa-link' }}" aria-hidden="true"></i> {{ link.label }}</a></li>
       {% endif %}
    {% endfor %}
  {% endif %}
</ul>



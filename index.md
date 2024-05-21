---
layout: default
title: María Mercedes Carranza en la Asamblea Nacional Constituyente
---

# HOLA

Esta edición digital busca mostrar el trabajo de María Mercedes Carranza como asambleísta en la Asamblea Nacional Constituyente de 1991. Esto por medio de la correspondencia y los recortes de prensa que reposan en su archivo personal (que se encuentra en custodia del Banco de Archivos Digitales de las Artes en Colombia -BADAC-), y el archivo de la ANC que reposa en el Archivo General de la Nación.

<hr>

<div class="toc">
  <h2>Algunos textos</h2>
  <ul class="texts">
  {% for item in site.texts %}
    <li class="text-title">
      <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
      </a>
    </li>
  {% endfor %}
  </ul>
</div>

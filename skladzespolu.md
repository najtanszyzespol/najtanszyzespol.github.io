---
layout: page
title: Sklad Zespolu
---
<ul>
{%for item in site.data.skladzespolu%}
  <li style="{% if item.isSinger %}color: blue {% endif %}">
    {{ item.name }}
  </li>
{%endfor%}
</ul>

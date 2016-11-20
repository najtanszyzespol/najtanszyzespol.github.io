---
layout: page
title: Skład zespołu
---
### Zapraszamy do zapoznania się z muzykami tworzącymi nasz zespół. Drugiej takiej ekipy nie znajdziecie nigdzie indziej!

*Kolorem niebieskim zaznaczono muzyków oswojonych z mikrofonem. Instrument nie jest problemem.  Co komu damy, to potrzyma i poudaje, że gra. Mikrofon to wyższa szkoła jazdy.*

<ul>
{%for item in site.data.skladzespolu%}
  <li style="{% if item.isSinger %}color: blue {% endif %}">
    {{ item.name }}
  </li>
	cena [PLN/noc]: {{ item.price }}
{%endfor%}
</ul>

**Instrumentarium do wyboru: **

+ dwie gitary marki Defil Lubin

+ zestaw dwóch garnków kuchennych, trzech patelni bez rączek i kosz na śmieci zaadoptowane do zastosowań perkusyjnych

+ grzebień z papierkiem

+ fujarka bieszczadzkiego pasterza owiec

+ deska z klawiszami udającymi pianino marki **Made in China**



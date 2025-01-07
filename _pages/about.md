---
permalink: /
title: "què farem?, què direm?"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hola! Sóc en Jan Ot, ara mateix visc a Holanda i estic fent un doctorat en Enginyeria Elèctrica a la Universitat Tècnica de Delft. Abans d'això era estudiant de Matemàtiques a Barcelona. La meva obsessió (o la més recent) els darrers temps ha sigut el cafè, les seves preparacions i el que s´hi amaga darrere. Així doncs sembla que utilitzaré aquesta pàgina per parlar de cafè, el que fem a la feina i altre miscel·lània. No espereu gaire constancia. 

Fins aviat,

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Jan Ot 



## Posts al Blog

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}

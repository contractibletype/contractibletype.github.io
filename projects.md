---
layout: page
title: Projectes
permalink: /projects/
---

![styled-image](/images/aachen.jpeg){: .align-center width="100%"}
<br>

Aquest text es una traducció aproximada del resum del meu projecte de doctorat.

# Multi-Energy System Smart-Linking Integration (MUESSLI)

En el context dels urgents esforços de descarbonització, la transició del petroli a l'electricitat i l'hidrogen com a contenidors d'energia és essencial. l'Hidrògen, idealment produït a través de l'electròlisi utilitzant l'energia sobrant de les FER (fonts d'energia renovables), pot servir com a alternativa a els Hidrocarburs. Tant l'hidrogen com l'electricitat jugaran papers vitals en les aplicacions d'ús final i sistemes de distribució.

El desenvolupament d'un sistema integrat d'hidrogen-electricitat requerirà de transformació i integració dels contenidors d'energia existents, com el metà, i les xarxes, incloent calefacció, refrigeració i transport, en el context local, regional i global. L'hidrogen haurà d'actuar com a catalitzador en el procés, ja en curs, de l'enllaç entre sectors. 

No obstant això, abans de la realització d'un sistema multienergia ens enfrontem a diversos reptes; La flexibilitat és crucial, ja que les qüestions i les tecnologies específiques del sector continuaran evolucionant, requereix l'adaptació contínua de leseines de simulació. L'estat tècnic actual dels mètodes de simulació no es suficient, de manera que alguna forma de "smart-linking" ha de ser desenvolupat.

El meu projecte de doctorat té com a objectiu modelar el comportament del sistema energètic anant més enllà dels supòsits de modelatge tradicionals, en particular els relacionats amb la competència perfecta i coordinació entre les parts interessades. També explorarà com el  "smart-linking" i els meta-models  poden servir per a abordar les limitacions dels models existents mitjançant la integració d'outputs que reflecteixen comportaments observats en aquests sistemes.

Una eina clau que permet ampliar l'abast d'aquesta recerca és la co-simulació, que enllaça múltiples models per millorar la representació de sistemes complexos. El focus d'aquest doctorat és estendre models mitjançant la cosimulació, utilitzant models basats en agents per creació i avaluació de proxy.

Mentre que la co-simulació amplia l'abast analític, també augmenta la complexitat de la  computació. El procés iteratiu requerit entre models pot ser poc pràctic per a estudis a gran escala . Per tant, s'utilitzaran meta-models per optimitzar el temps d'execució de la cosimulació mantenint els beneficis d'una anàlisi més integrada.

---

## Articles relacionats amb MueSSLi

<ul>
{% for post in site.categories.Doctorat %}
  <li>
    {{ post.date | date: "%d/%m/%Y" }} —
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
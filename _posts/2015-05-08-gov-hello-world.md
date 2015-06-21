---
layout: post
title:  "gov.hello_world()"
date:   2015-05-08 10:14:34
categories: artículo
---
### gov.hello_world()

Esto es una prueba. Repito. Esto es una prueba.

Un término comúnmente conocido entre la comunidad de programadores es el *hello world*, que generalmente se utiliza para probar que todo funcione y que estamos listos para comenzar.

Si queremos mantener y replicar esta funcionalidad entre diferentes
sistemas, una solución es encapsularla dentro de un paradigma conocido
como "programación orientada a objetos"; en otras palabras, una entidad
que tenga ciertas propiedades y comportamientos.

> "Si parece un pato, nada como un pato, y grazna como un pato, entonces probablemente sea un pato." - [La prueba del pato](http://es.wikipedia.org/wiki/Wikipedia:La_prueba_del_pato)

En el lenguaje de programación ruby, esto se vería así:

{% highlight ruby %}
un_pato.sabe_nadar?
#=> imprime 'true' en STDOUT.
gobierno.sabe_programar?
#=> imprime 'false' en STDOUT.
gobierno.responde_a?(:sus_ciudadanos)
#=> la aplicación se rompe
{% endhighlight %}

Ahora podemos entender que el título de este artículo es una abstracción para representar que hemos creado una instancia de una entidad "Gobierno" (gov: derivado de _Government_). Con esta copia de instancia podemos acceder a sus propiedades y funciones, crear nuevas copias, modificarlas, adaptarlas, mejorarlas y compartirlas. Visto en perspectiva, estamos probando que el código del gobierno funcione.

Esto no es sólo una prueba. Hoy en día estamos en la intersección de varios eventos que nos llevarán a este punto donde podremos modificar el funcionamiento del gobierno. El *open by default* como mejor práctica de gobierno, y la creciente tendencia de hackers involucrándose en temas cívicos lo hacen posible.

Sin embargo, se habla mucho del reto político y social, pero poco del reto
tecnológico.

> El gobierno necesita [hackers]({{site.baseurl}}/gobierno-necesita-hackers).

En [el siguiente artículo]({{site.basurl}}/por-que-estamos-aqui) describiremos a más detalle la razón de esto.

---

*Sobre el lenguaje*

El blog está en español porque está dirigido a una audiencia en América Latina, sin embargo se mantienen términos en inglés, ya que [este último se ha vuelto el lenguaje estándar en la Web](http://www.catb.org/esr/faqs/hacker-howto.html#skills4) y en particular en la industria de tecnología. Linus Torvalds, originario de Finlandia, no hubiera podido crear una comunidad internacional de *open source* escribiendo en finés.


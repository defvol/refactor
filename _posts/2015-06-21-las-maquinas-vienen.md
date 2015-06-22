---
layout: post
title:  "Las máquinas automatizarán la burocracia"
date:   2015-06-21 15:18:06
categories: articulo
---
Después de 2 años de ser testigo, juez, y parte de la implementación de una (y otras) política(s) en el gobierno federal, he notado que gran parte de mi trabajo (y el de otros) se puede redactar y automatizar con un par de simples algoritmos.

Por un lado están las tareas de seguimiento, como son revisar el avance de una dependencia de gobierno, hacer unas llamadas, escribir un par de correos, validar el cumplimiento, esperar un par de semanas (o meses) y repetir. Este tipo de algoritmos los podríamos llamar de látigo.

Pero no todo es seguimiento y normatividad, de ser así, no hubiera soportado ni 2 semanas en el gobierno. Tiene que haber algo más interesante, … sí, como las tareas de interpretación de la información. Esas que consisten en monitorear, recopilar datos, procesar y traducir un par de cosas, darles formato, y pasarlas al siguiente proceso. En algunos casos, inclusive, se requiere del juicio de un humano para clasificar esta información para coordinar el trabajo del siguiente eslabón en el proceso.

Todas estas tareas, hasta ahora, han requerido equipos humanos trabajando para mantener el barco a flote, y evitar fallas y contratiempos; que dada su naturaleza humana son inevitables.

Pero...

> ...los buenos programadores somos flojos y evitaremos a toda costa las tareas repetitivas y monótonas. Las herramientas y procesos inspirados en la pereza mejoran la productividad.

[How to be Lazy, Dumb, and Successful](http://blog.codinghorror.com/how-to-be-lazy-dumb-and-successful/).

Esta experiencia (y alergia a la repetición) me ha llevado a diseñar con varios equipos, una serie de proyectos que automatizarán tareas que actualmente hace el gobierno y algunas otras actividades que nunca realizará. A continuación platico un par de estos proyectos:

1. Todo empezo en 2014 con [ADELA](#adela), que da seguimiento a la Iniciativa de Datos Abiertos. Se asegura de que las dependencias del gobierno federal abran sus datos con los mejores estándares y en los tiempos acordados, llevándolos paso a paso por el proceso. También les hace recordatorios, y los califica. Imagina los cientos de correos, llamadas, y juntas de seguimiento que nos ahorramos.

2. El [_weatherman_](#weatherman) trabaja monitoreando el [Centro de Huracanes de la NOAA](http://www.nhc.noaa.gov/) para interpretar la información de un huracán y dejarla en formato entendible para los ciudadanos. También tiene una habilidad especial para calcular las costas más cercanas al centro de un ciclón en menos de 30ms (60,000 veces más rápido que el proceso humano actual). Próximamente te enviará avisos automáticos si te encuentras en una región vulnerable.

3. Hablando de huracanes, interpretar la información puede ser críptico para cualquier ciudadano no experto en meteorología. [NOE](#noe) es el primer centro de huracanes web. En una sóla página te presenta toda la información de ciclones con un mapa en tiempo real.

4. Una de las tareas que más tiempo nos consume es asegurar que los datos abiertos que publica el gobierno esten en buena forma. [VALI](#vali) sabe más de formatos y estándares abiertos que cualquier hacker cívico. Ella se encarga de revisar las publicaciones en [datos.gob.mx](http://datos.gob.mx) y validar una serie de condiciones de calidad necesarias para ofrecer un mejor servicio a los ciudadanos. También asesora al funcionario mostrándole videos y manuales específicos para realizar las mejoras que requiere su publicación.

5. A todos nos queda claro que interactuar con gobierno es tortuoso. Desde buscar información para becas hasta tramitar el acta de nacimiento resulta en un laberinto de información. [SARA](#sara) contesta todas tus dudas y te guía para que encuentres todo lo que necesites. En un futuro, por qué no, te resolverá tus trámites.

Esto es sólo el comienzo...

---

Si quieres seguir el avance de los proyectos (o contribuir), revisa [github.com/mxabierto](https://github.com/mxabierto) y [github.com/rodowi](https://github.com/rodowi), así como las ligas en este artículo (ojo: algunas ligas no funcionan dado que algunos blog posts están por escribirse).

Y si no me crees, ve el video [_Humans Not Need Apply_](https://twitter.com/rodowi/status/543449229583060992).

![Automation](https://imgs.xkcd.com/comics/automation.png)

[https://xkcd.com/1319/](https://xkcd.com/1319/)

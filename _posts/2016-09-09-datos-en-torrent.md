---
layout: post
title:  "Datos abiertos en BitTorrent"
date:   2016-09-09 08:25:00
categories: articulo
---

_Para asegurar disponibilidad de los datos abiertos, necesitamos descentralizar su distribución utilizando BitTorrent._

### ¿Cómo funciona BitTorrent en el contexto de datos abiertos?

En lugar de que miles de personas intenten bajar conjuntos de datos de un servidor lento y malconfigurado de gobierno, con BitTorrent los datos pueden ser distribuidos y compartidos en pequeños fragmentos y entre diferentes consumidores (y los mismos servidores originales).

La alta disponibilidad se asegura porque los datos tienen múltiples réplicas y la carga de la red se distribuye entre múltiples usuarios.

### ¿Cómo se puede empezar a distribuir datos abiertos en BitTorrent?

Esto no es nuevo, hay muchas herramientas y proyectos en esta línea, como [dat-project](http://dat-data.com), [maxogden/torrent](https://github.com/maxogden/torrent), [feross/bittorrent-tracker](https://github.com/feross/bittorrent-tracker), etc.

La comunidad de Codeando México [realizó una prueba de concepto](https://gist.github.com/rodowi/4ef366f9c8913a0779554ff1f2d17847) y ahora propone el siguiente plan:

- Distribuye archivos [.torrent](https://en.wikipedia.org/wiki/Torrent_file) para cada dataset en portales como datos.gob.mx, datamx.io.
- Cada vez que se utilicen clientes de BitTorrent para descargar datasets, la red obtendrá mayor capacidad de transferencia y replicabilidad.
- Tener un espejo de todos los datasets en un servicio de alta disponibilidad como Amazon S3. Conveniente para activar seeders rápidamente.
- Activar un par de seeders en servidores de gobierno y organizaciones con capacidad de cómputo para la banda (p. ej. INEGI, UNAM). Descargan el espejo y comienzan a ser seeders.
- Además de utilizar trackers públicos [ya disponibles](https://en.wikipedia.org/wiki/Comparison_of_BitTorrent_sites) se debe activar un tracker de la comunidad de datos abiertos (externo a gobierno).

### Referencias:

- [BitTorrent](https://es.wikipedia.org/wiki/BitTorrent) - Wikipedia
- [How DAT works](https://dat-data.readthedocs.io/en/latest/how-dat-works/) - dat-data.readthedocs.io
- [What are the practical limits of releasing open data via bit torrent?](http://opendata.stackexchange.com/questions/283/what-are-the-practical-limits-of-releasing-open-data-via-bit-torrent) - StackExchange
- [Recommended BitTorrent tracker/index for dataset release?](http://opendata.stackexchange.com/questions/811/recommended-bittorrent-tracker-index-for-dataset-release/843#843) - StackExchange

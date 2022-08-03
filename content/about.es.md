---
date: 2021-11-17
title: "Acerca de TLDR Pages"
description: "¿Qué es TLDR Pages? ¿Cómo contribuir? ¿Qué es este sitio web?"
---

> Advertencia: esta página se traduce automáticamente - a diferencia de TLDR Pages en este sitio web - por lo que podría haber errores de traducción

![TLDR Pages Logo](/tldr-logo.png)

|Gitter|PRs|Contributors|Build Status|LICENSE|
|---|---|---|---|---|
[![Gitter chat][gitter-image]][gitter-url]|[![Merged PRs][prs-merged-image]][prs-merged-url]|[![GitHub contributors][contributors-image]][contributors-url]|[![Build status][github-actions-image]][github-actions-url]|[![license][license-image]][license-url]

[github-actions-url]: https://github.com/tldr-pages/tldr/actions
[github-actions-image]: https://img.shields.io/github/workflow/status/tldr-pages/tldr/CI.svg
[gitter-url]: https://gitter.im/tldr-pages/tldr
[gitter-image]: https://img.shields.io/badge/chat-on_gitter-deeppink
[prs-merged-url]: https://github.com/tldr-pages/tldr/pulls?q=is:pr+is:merged
[prs-merged-image]: https://img.shields.io/github/issues-pr-closed-raw/tldr-pages/tldr.svg?label=merged+PRs&color=green
[contributors-url]: https://github.com/tldr-pages/tldr/graphs/contributors
[contributors-image]: https://img.shields.io/github/contributors-anon/tldr-pages/tldr.svg
[license-url]: https://github.com/tldr-pages/tldr/blob/main/LICENSE.md
[license-image]: https://img.shields.io/badge/license-CC_BY_4.0-blue.svg
</div>

## ¿Qué es tldr-pages?

El proyecto **tldr-pages** es una colección de páginas de ayuda mantenidas en colaboración
para las herramientas de línea de comandos que proporcionan un complemento más sencillo y accesible a los
a las tradicionales [páginas man](https://en.wikipedia.org/wiki/Man_page).

¿Quizás eres nuevo en el mundo de las líneas de comando? ¿Quizás estés un poco oxidado o no recuerdes siempre los argumentos de comandos como `lsof` o `tar`?

Ciertamente no ayuda que la primera opción explicada en `man tar` sea:

```
-b bloque
   Especifica el tamaño del bloque, en registros de 512 bytes, para la E/S de la unidad de cinta.
   Normalmente este argumento sólo es necesario cuando se lee o escribe en unidades de cinta,
   y normalmente ni siquiera así, ya que el tamaño de bloque por defecto de 20 registros (10240 bytes) es muy común.
```

Parece que hay espacio para páginas de ayuda más sencillas que se centren en ejemplos prácticos.
Que tal:

![SVG animado del cliente tldr mostrando el comando tar](/tldr-tar.svg)

> La página TLDR para el comando tar también se puede encontrar en este sitio web [este enlace](https://tldr.bortox.it/common/tar)

Este repositorio es precisamente eso: una colección de ejemplos en constante crecimiento.
para las herramientas de línea de comandos más comunes de UNIX, Linux, macOS, SunOS, Android y Windows.

## ¿Qué es este sitio?

El propósito de este sitio es hacer que las Páginas TLDR, una colección de páginas de ayuda gestionadas por la comunidad
para herramientas de línea de comandos_ a los usuarios de la web simplemente escribiendo 'páginas TLDR + nombre_de_comando' en su motor de búsqueda favorito.

Actualmente, no es posible encontrar la página TLDR de un comando con una simple búsqueda en Google. La situación es aún peor cuando se busca un comando en un idioma específico que no sea el inglés, ya que a menudo hay sitios web lentos y de clickbait.

De hecho, este sitio también admite comentarios y la posibilidad de compartir, lo que hace que las páginas TLDR sean "amigables con la web". 

### Análisis, seguimiento y anuncios

Por supuesto, no hay **publicidad**. 

El seguimiento se realiza con Matomo. Matomo está configurado para no recopilar **datos personales**[^1], por lo que cumple con el GDPR y no requiere cookies de banner. [Si desea excluirse, puede hacerlo aquí](https://stats.bortox.it/index.php?module=CoreAdminHome&action=optOut&language=it).

El sitio está **alojado en Europa**, por PHP-Friends. Según web-carbon.com, el centro de datos utiliza **energía sostenible**.

Si quieres **apoyar** el sitio (yo pago los servidores), puedes [**donar algo aquí**](https://bortox.it/contribuisci-cs-en).

### ¿Por qué este sitio?

1. indexar las páginas de TLDR y facilitar su búsqueda en línea en varios idiomas
2. sólo para escribir algo

### ¿Cómo funciona este sitio?

* Los archivos fuente TLDR en Markdown y los datos Git asociados se leen desde un script (30m).
* Las páginas compatibles con Hugo son creadas por el script
* ¡Hugo crea este sitio web (~6500 páginas) en sólo 10 segundos!

### Posibles nuevas características

- [ ] Páginas específicas de compromiso
- Traducción automática con DeepL (hasta 500.000 caracteres/mes en la versión gratuita)


## Cómo se usa

Una forma popular y cómoda de acceder a estas páginas en su propio ordenador
es instalar el [cliente Node.js](https://github.com/tldr-pages/tldr-node-client),
que cuenta con el apoyo de los mantenedores del proyecto tldr-pages:

``sh
npm install -g tldr
```

Como alternativa, puede utilizar el [cliente Python](https://github.com/tldr-pages/tldr-python-client), que puede instalarse a través de `pip3`.

``sh
pip3 install tldr
```

Esto le da acceso directo a una guía simplificada y fácil de leer de comandos como `tar`,
accesible escribiendo `tldr tar` en lugar del normal `man tar`.

Si quieres una versión offline sin instalar ningún software,
ver la [versión PDF](https://tldr.sh/assets/tldr-book.pdf).

Para navegar sin instalar un cliente en su ordenador
ver el cliente web en <https://tldr.ostera.io>.

También hay **otros clientes** proporcionados por la comunidad,
tanto para la línea de comandos como para otras plataformas.
Para ver la lista completa de clientes, consulte nuestra [wiki](https://github.com/tldr-pages/tldr/wiki/tldr-pages-clients).


## ¿Cómo puedo contribuir a tldr-pages?

Todas las contribuciones son bienvenidas.

Algunas formas de contribuir son

- Añadir su comando favorito que no está cubierto.
- Añadir ejemplos o mejorar el contenido de una página existente.
- Añadir páginas solicitadas de nuestros números con la etiqueta [help wanted](https://github.com/tldr-pages/tldr/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22).
- Traducción de páginas a diferentes idiomas.

Todas las páginas de `tldr` están escritas en Markdown, por lo que se pueden editar con bastante facilidad y los cambios se pueden hacer en
con Git en la línea de comandos o a través del
a través de la interfaz web de GitHub.

Nos esforzamos por mantener una comunidad [acogedora y colaboradora](https://github.com/tldr-pages/tldr/blob/main/GOVERNANCE.md).
Si es la primera vez que contribuyes, echa un vistazo a las [Directrices de contribución](https://github.com/tldr-pages/tldr/blob/main/CONTRIBUTING.md), ¡y empieza!

Si quieres contribuir a las traducciones, puedes <https://lukwebsforge.github.io/tldri18n/>
para ver el progreso general de todas las traducciones y saber qué traducciones faltan o están obsoletas.


## ¿Qué significa 'tldr'?

TL;DR significa "Demasiado largo; no he leído".
Deriva de la jerga de Internet, donde se utiliza para indicar que un texto largo (o partes de él) ha sido
(o parte de él) se ha omitido por ser demasiado largo.
Más información en [artículo] de How-To Geek (https://www.howtogeek.com/435266/what-does-tldr-mean-and-how-do-you-use-it/).

[^1]: Sin registros de visitas, seguimiento sin cookies, direcciones IP anónimas (2 bytes, como 192.168.xxx.xxx ) según la [guía oficial de matomo](https://matomo.org/faq/new-to-piwik/how-do-i-use-matomo-analytics-without-consent-or-cookie-banner/) ... 


---
author: ['Mario Gordon', 'marchersimon']
date: 1659075216
title: "service, TLDR Pages"
description: "service, Gestiona los servicios mediante la ejecución de scripts init."
categories: "linux"
---
> Se debe omitir la ruta completa del script (se asume `/etc/init.d/`).

> Más información: <https://manned.org/service>.

- Lista el nombre y el estado de todos los servicios:

```bash
service --status-all
```

- Inicia/Para/Reinicia/Recarga servicio (_start_/_stop_ debería estar siempre disponible):

```bash
service nombre_de_servicio start|stop|restart|reload
```

- Hace un reinicio completo (ejecuta el script dos veces con _start_ y _stop_):

```bash
service nombre_de_servicio --full-restart
```

- Muestra el estado actual de un servicio:

```bash
service nombre_de_servicio status
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Mario Gordon](mailto:80539604+maegop@users.noreply.github.com) | service: add Spanish translation (#7311) | 2021-11-02T23:09:54 | [5e22b5d56b12](https://github.com/tldr-pages/tldr/commit/5e22b5d56b12fda02e73bb397306c90ff25ee5ef)


---
author: ['Seifer23']
date: 1644117941
title: "service, TLDR Pages"
description: "service, Gestiona els serveis mitjançant l'execució de scripts init."
categories: "linux"
---
> S'ha d'ometre la ruta completa del script (s'assumeix `/etc/init.d`).

- Llista el nom i l'estat de tots els serveis:

```bash
service --status-all
```

- Inicia/Para/Reinicia/Recarrega servei (_start_/_stop_ hauria d'estar sempre disponible):

```bash
service nom_del_servei start|stop|restart|reload
```

- Fa un reinici complet (executa el script dues vegades amb _start_ i _stop_):

```bash
service nom_del_servei --full-restart
```

- Mostra l'estat actual d'un servei:

```bash
service nom_del_servei status
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)


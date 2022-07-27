---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker logs, TLDR Pages"
description: "docker logs, Zeige Container Logs."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/logs>.

- Zeige die Logs eines Containers:

```bash
docker logs container_name
```

- Zeige die Logs und aktualisiere sie automatisch:

```bash
docker logs -f container_name
```

- Zeige die letzten 5 Zeilen:

```bash
docker logs container_name --tail 5
```

- Zeige die Logs und füge ihnen Zeitstempel hinzu:

```bash
docker logs -t container_name
```

- Zeige Logs vor einem bestimmten Zeitpunkt der Ausführung des Containers (bspw. 23m, 10s, 2013-01-02T13:23:37):

```bash
docker logs container_name --until time
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


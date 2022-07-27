---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker system, TLDR Pages"
description: "docker system, Verwalte Docker Daten und zeige systemweite Informationen an."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/system/>.

- Zeige Hilfe:

```bash
docker system
```

- Zeige Docker Festplattennutzung:

```bash
docker system df
```

- Zeige detaillierte Informationen zur Festplattennutzung:

```bash
docker system df --verbose
```

- Entferne nicht-verwendete Daten:

```bash
docker system prune
```

- Entferne nicht-verwendete Daten, die älter als die angegeben Zeit sind:

```bash
docker system prune --filter="until=stundenhminutenm"
```

- Zeige Echtzeit-Events vom Docker Daemon:

```bash
docker system events
```

- Zeige Echtzeit-Events von Containern und formatiere jede Zeile als gültiges JSON:

```bash
docker system events --filter 'type=container' --format 'json .'
```

- Zeige systemweite Informationen:

```bash
docker system info
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


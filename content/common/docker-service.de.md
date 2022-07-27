---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker service, TLDR Pages"
description: "docker service, Verwalte Docker Services."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/service/>.

- Liste alle Services auf:

```bash
docker service ls
```

- Erstelle einen neuen Service:

```bash
docker service create --name service_name image:tag
```

- Zeige detaillierte Informationen der mit Leerzeichen separierten Services an:

```bash
docker service inspect service_name|ID
```

- Liste die Tasks der mit Leerzeichen separierten Services auf:

```bash
docker service ps service_name|ID
```

- Skaliere die angegebenen Services auf einen bestimmte Anzahl an Replikaten:

```bash
docker service scale service_name=anzahl_an_replikaten
```

- Lösche die mit Leerzeichen separierten Services:

```bash
docker service rm service_name|ID
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


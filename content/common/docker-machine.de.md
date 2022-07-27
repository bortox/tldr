---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker-machine, TLDR Pages"
description: "docker-machine, Erstelle und verwalte Maschinen, die Docker ausführen."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/machine/reference/>.

- Liste zur Zeit laufende Docker Maschinen auf:

```bash
docker-machine ls
```

- Erzeuge eine neue Docker Maschine mit einem spezifischen Namen:

```bash
docker-machine create name
```

- Zeige den Status einer Maschine:

```bash
docker-machine status name
```

- Starte eine Maschine:

```bash
docker-machine start name
```

- Stoppe eine Maschine:

```bash
docker-machine stop name
```

- Zeige Informationen über eine Maschine:

```bash
docker-machine inspect name
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


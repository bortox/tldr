---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker-slim, TLDR Pages"
description: "docker-slim, Analysiere und optimiere Docker Images."
categories: "common"
---
> Weitere Informationen: <https://github.com/docker-slim/docker-slim>.

- Starte DockerSlim im interaktiven Modus:

```bash
docker-slim
```

- Analysiere die Docker Layer eines bestimmten Images:

```bash
docker-slim xray --target image:tag
```

- Linte ein Dockerfile:

```bash
docker-slim lint --target pfad/zum/Dockerfile
```

- Analysiere und generiere ein optimiertes Docker Image:

```bash
docker-slim build image:tag
```

- Zeige Hilfe für einen Unterbefehl:

```bash
docker-slim unterbefehl --help
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


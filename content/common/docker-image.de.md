---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker image"
description: "docker image, Verwalte Docker Images."
categories: "common"
---
> Siehe auch `docker build`, `docker import` und `docker pull`.

> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/image/>.

- Liste lokale Docker Images auf:

```bash
docker image ls
```

- Lösche nicht verwendete, lokale Docker Images:

```bash
docker image prune
```

- Lösche alle nicht verwendeten Docker Images (nicht nur die ohne Tag):

```bash
docker image prune --all
```

- Zeige die Geschichte eines lokalen Docker Images:

```bash
docker image history image
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


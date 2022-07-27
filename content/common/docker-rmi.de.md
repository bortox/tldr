---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker rmi, TLDR Pages"
description: "docker rmi, Lösche eines oder mehrere Docker Images."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/rmi/>.

- Zeige Hilfe:

```bash
docker rmi
```

- Lösche eines oder mehrere Docker Images anhand der angegebenen Namen:

```bash
docker rmi image1 image2 ...
```

- Erzwinge das Löschen eines Images:

```bash
docker rmi --force image
```

- Lösche ein Image aber behalte Eltern-Images ohne Tag:

```bash
docker rmi --no-prune image
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


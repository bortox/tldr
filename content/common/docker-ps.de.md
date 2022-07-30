---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker ps"
description: "docker ps, Liste Docker Container."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/ps/>.

- Liste zur Zeit laufende Container auf:

```bash
docker ps
```

- Liste laufende und gestoppte Container auf:

```bash
docker ps --all
```

- Zeige den zuletzt erstellten Container (berücksichtigt jeden Status):

```bash
docker ps --latest
```

- Zeige nur Container mit einer bestimmten Zeichenkette im Namen:

```bash
docker ps --filter="name=name"
```

- Zeige nur Container die von einem bestimmten Image abstammen:

```bash
docker ps --filter "ancestor=image:tag"
```

- Zeige nur Container mit einem bestimmten Exit-Code:

```bash
docker ps --all --filter="exited=code"
```

- Zeige nur Container mit einem bestimmten Status (created, running, removing, paused, exited und dead):

```bash
docker ps --filter="status=status"
```

- Zeige nur Container, welche einen bestimmten Datenträger oder einen Datenträger an einem bestimmten Pfad eingehängt haben:

```bash
docker ps --filter="volume=pfad/zum/verzeichnis" --format "table .ID\t.Image\t.Names\t.Mounts"
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


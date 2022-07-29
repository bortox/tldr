---
author: ['Muhammad Falak R Wani', 'Joachim Schwarm']
date: 1659013407
title: "docker run, TLDR Pages"
description: "docker run, Führe einen Befehl in einem neuen Docker Container aus."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/run/>.

- Führe einen Befehl in einem neuen Docker Container aus und verwende dabei einen bestimmten Tag eines Docker Images:

```bash
docker run image:tag befehl
```

- Führe einen Befehl in einem neuen Container im Hintergrund aus und zeige die ID:

```bash
docker run --detach image befehl
```

- Führe einen Befehl in einem kurzlebigen Container im interaktiven Modus mit einem Pseudo-TTY aus:

```bash
docker run --rm --interactive --tty image befehl
```

- Führe einen Befehl in einem neuen Container mit übergebenen Umgebungsvariablen aus:

```bash
docker run --env 'variable=wert' --env variable image befehl
```

- Führe einen Befehl in einem neuen Container mit eingebundenen Datenträgern aus:

```bash
docker run --volume pfad/zu/host_verzeichnis:pfad/zu/container_verzeichnis image befehl
```

- Führe einen Befehl in einem neuen Container mit veröffentlichten Ports aus:

```bash
docker run --publish host_port:container_port image befehl
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | docker-run: use long options for examples (#8262) | 2022-07-28T15:03:27 | [b7c8b55849e7](https://github.com/tldr-pages/tldr/commit/b7c8b55849e7ace9394c375e6533a920682c0a78)
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


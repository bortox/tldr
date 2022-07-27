---
author: ['Joachim Schwarm']
date: 1634445390
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
docker run -d image befehl
```

- Führe einen Befehl in einem kurzlebigen Container im interaktiven Modus mit einem Pseudo-TTY aus:

```bash
docker run --rm -it image befehl
```

- Führe einen Befehl in einem neuen Container mit übergebenen Umgebungsvariablen aus:

```bash
docker run -e 'variable=wert' -e variable image befehl
```

- Führe einen Befehl in einem neuen Container mit eingebundenen Datenträgern aus:

```bash
docker run -v pfad/zu/host_verzeichnis:pfad/zu/container_verzeichnis image befehl
```

- Führe einen Befehl in einem neuen Container mit veröffentlichten Ports aus:

```bash
docker run -p host_port:container_port image befehl
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


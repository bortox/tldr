---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker exec, TLDR Pages"
description: "docker exec, Führe Befehle in einem bereits laufenden Docker Container aus:"
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/exec/>.

- Öffne eine Shell innerhalb eines bereits laufenden Containers:

```bash
docker exec --interactive --tty container_name /bin/bash
```

- Führe einen Befehl im Hintergrund (losgelöst) in einem laufenden Container aus:

```bash
docker exec --detach container_name befehl
```

- Bestimme das Arbeitsverzeichnis, in dem der Befehl ausgeführt werden soll:

```bash
docker exec --interactive -tty --workdir pfad/zum/verzeichnis container_name befehl
```

- Führe einen Befehl im Hintergrund in einem laufenden Container aus, aber lies von der Standardeingabe:

```bash
docker exec --interactive --detach container_name befehl
```

- Setze eine Umgebungsvariable in einer laufenden Bash Sitzung:

```bash
docker exec --interactive --tty --env variablen_name=wert container_name /bin/bash
```

- Führe einen Befehl als ein bestimmter Benutzer aus:

```bash
docker exec --user benutzer container_name befehl
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


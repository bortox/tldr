---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker cp"
description: "docker cp, Kopiere Dateien oder Verzeichnisse zwischen Host- und Container-Dateisystem."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/cp>.

- Kopiere eine Datei oder ein Verzeichnis vom Host in einen Container:

```bash
docker cp pfad/zu/datei_oder_verzeichnis_auf_host container_name:pfad/zu/datei_oder_verzeichnis_in_container
```

- Kopiere eine Datei oder ein Verzeichnis von einem Container zum Host:

```bash
docker cp container_name:pfad/zu/datei_oder_verzeichnis_in_container pfad/zu/datei_oder_verzeichnis_auf_host
```

- Kopiere eine Datei oder ein Verzeichnis vom Host in einen Container und folge dabei Symlinks (kopiert die verlinkten Dateien statt der Symlinks):

```bash
docker cp --follow-link pfad/zu/symlink_auf_host container_name:pfad/zu/datei_oder_verzeichnis_in_container
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker save"
description: "docker save, Exportiere eines oder mehrere Docker Images in ein Archiv."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/save/>.

- Speichere ein Image über die Standardausgabe in ein Tar-Archiv:

```bash
docker save image:tag > pfad/zur/datei.tar
```

- Speichere ein Image in ein Tar-Archiv:

```bash
docker save --output pfad/zur/datei.tar image:tag
```

- Speichere alle Tags eines Images:

```bash
docker save --output pfad/zur/datei.tar image_name
```

- Speichere nur bestimmte Tags eines Images:

```bash
docker save --output pfad/zur/datei.tar image_name:tag1 image_name:tag2 ...
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


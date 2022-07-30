---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker images"
description: "docker images, Verwalte Docker Images."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/images/>.

- Liste alle Docker Images auf:

```bash
docker images
```

- Liste alle Docker Images inkl. Zwischen-Images auf:

```bash
docker images --all
```

- Liste nur die IDs der Docker Images auf:

```bash
docker images --quiet
```

- Liste alle Docker Images auf, die nicht von einem Container verwendet werden:

```bash
docker images --filter dangling=true
```

- Liste alle Docker Images mit einer bestimmten Zeichenfolge im Namen auf:

```bash
docker images "*name*"
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


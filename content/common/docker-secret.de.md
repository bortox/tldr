---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker secret, TLDR Pages"
description: "docker secret, Verwalte Secrets für Docker Swarm."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/secret/>.

- Erstelle ein neues Secret über die Standardeingabe:

```bash
befehl | docker secret create secret_name -
```

- Erstelle ein neues Secret aus einer Datei:

```bash
docker secret create secret_name pfad/zur/datei
```

- Liste alle Secrets auf:

```bash
docker secret ls
```

- Zeige detaillierte Informationen zu einem oder mehreren Secrets in einem menschenlesbaren Format:

```bash
docker secret inspect --pretty secret_name1 secret_name2 ...
```

- Lösche eines oder mehrere Secrets:

```bash
docker secret rm secret_name1 secret_name2 ...
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


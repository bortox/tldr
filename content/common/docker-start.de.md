---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker start"
description: "docker start, Starte einen oder mehrere gestoppte Container."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/start/>.

- Zeige Hilfe:

```bash
docker start
```

- Starte einen Docker Container:

```bash
docker start container
```

- Starte einen Container und verbinde dich mit der Standardausgabe sowie der Standardfehlerausgabe und leite Signale weiter:

```bash
docker start --attach container
```

- Starte einen oder mehrere durch Leerzeichen getrennte Container:

```bash
docker start container
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


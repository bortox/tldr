---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker build"
description: "docker build, Baut ein Image aus einem Dockerfile."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/build/>.

- Baue ein Docker Image aus dem Dockerfile im aktuellen Verzeichnis:

```bash
docker build .
```

- Baue ein Docker Image aus einem Dockerfile an einer angegebenen URL:

```bash
docker build github.com/creack/docker-firefox
```

- Baue ein Docker Image und gib ihm einen Tag:

```bash
docker build --tag name:tag .
```

- Baue ein Docker Image ohne Build-Kontext:

```bash
docker build --tag name:tag - < Dockerfile
```

- Verwende keinen Cache beim Bauen des Docker Images:

```bash
docker build --no-cache --tag name:tag .
```

- Baue ein Docker Image mit einem spezifischen Dockerfile:

```bash
docker build --file Dockerfile .
```

- Baue mit benutzerdefinierten Variablen, die während des Bauens zur Verfügung stehen:

```bash
docker build --build-arg HTTP_PROXY=http://10.20.30.2:1234 --build-arg FTP_PROXY=http://40.50.60.5:4567 .
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


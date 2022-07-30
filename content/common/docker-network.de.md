---
author: ['Joachim Schwarm', 'Daniel']
date: 1634914980
title: "docker network"
description: "docker network, Erzeuge und verwalte Docker Netzwerke."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/network/>.

- Liste alle verfügbaren und konfigurierten Docker Netzwerke auf:

```bash
docker network ls
```

- Erzeuge ein benutzerdefiniertes Netzwerk:

```bash
docker network create --driver treiber_name netzwerk_name
```

- Zeige detaillierte Informationen der mit Leerzeichen separierten Netzwerke an:

```bash
docker network inspect netzwerk_name
```

- Verbinde einen Container mit einem Netzwerk anhand des Namens oder der ID:

```bash
docker network connect netzwerk_name container_name|ID
```

- Trenne einen Container von einem Netzwerk:

```bash
docker network disconnect netzwerk_name container_name|ID
```

- Entferne alle unbenutzten (nicht von Containern referenzierten) Netzwerke:

```bash
docker network prune
```

- Entferne mehrere - durch Leerzeichen getrennte - Netzwerke:

```bash
docker network rm netzwerk_name
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


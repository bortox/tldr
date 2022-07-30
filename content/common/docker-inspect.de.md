---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker inspect"
description: "docker inspect, Erhalte tiefgehende Informationen zu Docker Objekten."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/inspect/>.

- Zeige Hilfeseite:

```bash
docker inspect
```

- Zeige Informationen über einen Container, ein Image oder Volume anhand des Namens oder der ID:

```bash
docker inspect container|image|ID
```

- Zeige die IP Adresse eines Containers an:

```bash
docker inspect --format='range .NetworkSettings.Networks.IPAddressend' container
```

- Zeige den Pfad zur Logdatei eines Containers:

```bash
docker inspect --format='.LogPath' container
```

- Zeige den Namen des Images eines Containers:

```bash
docker inspect --format='.Config.Image' container
```

- Zeige die Konfiguration als JSON an:

```bash
docker inspect --format='json .Config' container
```

- Zeige alle Port Bindings:

```bash
docker inspect --format='range $p, $conf := .NetworkSettings.Ports $p -> (index $conf 0).HostPort end' container
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


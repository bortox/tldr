---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker swarm, TLDR Pages"
description: "docker swarm, Ein Container-Orchestrierungswerkzeug."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/swarm/>.

- Initialisiere ein Swarm Cluster:

```bash
docker swarm init
```

- Zeige den Token um als Manager oder Worker beizutreten:

```bash
docker swarm join-token worker|manager
```

- Füge dem Cluster eine neue Node hinzu:

```bash
docker swarm join --token token manager_node_url:2377
```

- Entferne einen Worker vom Swarm (führe dies auf der Worker Node aus):

```bash
docker swarm leave
```

- Zeige die aktuellen CA Zertifikate im PEM Format:

```bash
docker swarm ca
```

- Rotiere die aktuellen CA Zertifikate und zeige die neuen Zertifikate:

```bash
docker swarm ca --rotate
```

- Ändere die Gültigkeitsdauer für Node-Zertifikate:

```bash
docker swarm update --cert-expiry stundenhminutenmsekundens
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


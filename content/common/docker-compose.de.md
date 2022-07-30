---
author: ['Locour', 'Joachim Schwarm']
date: 1634445390
title: "docker-compose"
description: "docker-compose, Starte und verwalte Anwendungen, welche aus mehreren Docker Containern bestehen."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/compose/reference/>.

- Liste alle laufenden Container auf:

```bash
docker-compose ps
```

- Erzeuge und starte alle Container im Hintergrund unter der Verwendung der Datei `docker-compose.yml` im aktuellen Verzeichnis:

```bash
docker-compose up -d
```

- Starte alle Container. Erzeuge zugehörige Docker Images bei Bedarf neu:

```bash
docker-compose up --build
```

- Starte alle Container unter Verwendung einer alternativen Compose Datei:

```bash
docker-compose --file pfad/zu/verzeichnis up
```

- Stoppe alle laufenden Container:

```bash
docker-compose stop
```

- Stoppe und entferne alle Container inklusive zugehöriger Netzwerke, Volumes und Images:

```bash
docker-compose down --rmi all --volumes
```

- Zeige die Logs aller Container kontinuierlich an:

```bash
docker-compose logs --follow
```

- Zeige die Logs eines spezifischen Containers kontinuierlich an:

```bash
docker-compose logs --follow container_name
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)
[Locour](mailto:Locour@users.noreply.github.com) | docker-compose: add German translation (#6978) | 2021-10-13T19:23:45 | [9e781d59bed6](https://github.com/tldr-pages/tldr/commit/9e781d59bed60863bbf0de866c5f181d8622514e)


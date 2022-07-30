---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker container"
description: "docker container, Verwalte Docker Container."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/container/>.

- Liste zur Zeit laufende Container auf:

```bash
docker container ls
```

- Starte einen oder mehrere gestoppte Container:

```bash
docker container start container1_name container2_name
```

- Beende einen oder mehrere laufende Container sofort:

```bash
docker container kill container_name
```

- Stoppe einen oder mehrere laufende Container:

```bash
docker container stop container_name
```

- Pausiere alle Prozesse in einem oder mehreren Containern:

```bash
docker container pause container_name
```

- Zeige detaillierte Informationen zu einem oder mehreren Containern an:

```bash
docker container inspect container_name
```

- Exportiere das Dateisystem eines Containers als tar Archiv:

```bash
docker container export container_name
```

- Erstelle ein neues Image aus den Änderungen eines Containers:

```bash
docker container commit container_name
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


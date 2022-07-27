---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker stats, TLDR Pages"
description: "docker stats, Zeige den Ressourcen-Verbrauch von Containern in Echtzeit."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/stats/>.

- Zeige sich stetig aktualisierende Statistiken von allen laufenden Containern:

```bash
docker stats
```

- Zeige sich stetig aktualisierende Statistiken der durch Leerzeichen getrennten Container:

```bash
docker stats container_name
```

- Ändere das Spaltenformat um die CPU Auslastung von Containern in Prozent anzuzeigen:

```bash
docker stats --format ".Name:\t.CPUPerc"
```

- Zeige Statistiken für alle Container (laufende und gestoppte):

```bash
docker stats --all
```

- Deaktiviere die laufende Aktualisierung und zeige nur die aktuellen Statistiken:

```bash
docker stats --no-stream
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


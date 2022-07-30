---
author: ['Joachim Schwarm']
date: 1634445390
title: "docker login"
description: "docker login, Bei einer Docker Registry einloggen."
categories: "common"
---
> Weitere Informationen: <https://docs.docker.com/engine/reference/commandline/login/>.

- Interaktives Einloggen bei einer Registry:

```bash
docker login
```

- Einloggen mit einem angegebenen Benutzernamen (fragt nach dem Passwort):

```bash
docker login --username benutzername
```

- Einloggen mit einem angegebenen Benutzernamen und Passwort:

```bash
docker login --username benutzername --password passwort server
```

- Einloggen mit einem Passwort, welches von stdin gelesen wird:

```bash
echo "passwort" | docker login --username benutzername --password-stdin
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)


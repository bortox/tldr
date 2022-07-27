---
author: ['Michael Schwarz']
date: 1635777041
title: "add-apt-repository, TLDR Pages"
description: "add-apt-repository, Verwalte apt-Repository Definitionen."
categories: "linux"
---
> Weitere Informationen: <https://manned.org/apt-add-repository>.

- Füge ein neues apt-Repository hinzu:

```bash
add-apt-repository repository_spec
```

- Entferne ein apt-Repository:

```bash
add-apt-repository --remove repository_spec
```

- Aktualisiere den Paketcache nach dem Hinzufügen eines Repositories:

```bash
add-apt-repository --update repository_spec
```

- Erlaube das Herunterladen von Quellpaketen aus dem Repository:

```bash
add-apt-repository --enable-source repository_spec
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Michael Schwarz](mailto:michael089+github@outlook.de) | add-apt-repository: add German translation (#7202) | 2021-11-01T15:30:41 | [f140aec06d7b](https://github.com/tldr-pages/tldr/commit/f140aec06d7be8adff32abaffdf0addef2e5d1f6)


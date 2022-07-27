---
author: ['Mastercuber']
date: 1643882992
title: "abbr, TLDR Pages"
description: "abbr, Abkürzungen für die fish shell verwalten."
categories: "linux"
---
> Die vom Nutzer definierten Abkürzungen werden nach der Eingabe durch die Langversionen ersetzt.

> Mehr Informationen: <https://fishshell.com/docs/current/cmds/abbr.html>.

- Neue Abkürzung hinzufügen:

```bash
abbr --add abkürzungsname befehl befehlsparameter
```

- Vorhandene Abkürzung umbenennen:

```bash
abbr --rename alter_name neuer_name
```

- Vorhandene Abkürzung löschen:

```bash
abbr --erase abkürzungsname
```

- Abkürzungen eines anderen Host über SSH importieren:

```bash
ssh host_name abbr --show | source
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Mastercuber](mailto:mr_w@posteo.de) | alien, abbr: add German translation (#7651) | 2022-02-03T11:09:52 | [07c853b70af1](https://github.com/tldr-pages/tldr/commit/07c853b70af1e865ef69d29251ea09fc0442dc63)


---
author: ['marchersimon', 'Mastercuber']
date: 1659075216
title: "abbr, TLDR Pages"
description: "abbr, Abkürzungen für die fish shell verwalten."
categories: "linux"
---
> Die vom Nutzer definierten Abkürzungen werden nach der Eingabe durch die Langversionen ersetzt.

> Weitere Informationen: <https://fishshell.com/docs/current/cmds/abbr.html>.

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
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Mastercuber](mailto:mr_w@posteo.de) | alien, abbr: add German translation (#7651) | 2022-02-03T11:09:52 | [07c853b70af1](https://github.com/tldr-pages/tldr/commit/07c853b70af1e865ef69d29251ea09fc0442dc63)


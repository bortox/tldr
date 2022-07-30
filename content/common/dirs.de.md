---
author: ['Pierre Hoffmeister']
date: 1634019057
title: "dirs"
description: "dirs, Zuletzt besuchte Ordner anzeigen und verändern."
categories: "common"
---
> Die Liste der zuletzt besuchten Ordner kann mit `pushd` und `popd` verändert werden.

> Weitere Informationen: <https://www.gnu.org/software/bash/manual/bash.html#Directory-Stack-Builtins>.

- Zeige die zuletzt besuchten Ordner durch Leerzeichen getrennt an:

```bash
dirs
```

- Zeige die zuletzt besuchten Ordner mit einem Eintrag pro Zeile an:

```bash
dirs -p
```

- Zeige den N-ten Eintrag der zuletzt besuchten Ordner an, beginnend mit 0:

```bash
dirs +N
```

- Leere die Liste der zuletzt besuchten Ordner:

```bash
dirs -c
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Pierre Hoffmeister](mailto:1093398+phoffmeister@users.noreply.github.com) | dirs: add German translation (#6860) | 2021-10-12T08:10:57 | [be1e7b9d5ccf](https://github.com/tldr-pages/tldr/commit/be1e7b9d5ccfb79377e7865ba492db02a2855d83)


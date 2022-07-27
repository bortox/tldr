---
author: ['S-Espinet']
date: 1635946689
title: "export, TLDR Pages"
description: "export, Befehl zum Markieren von Shell-Variablen in der aktuellen Umgebung, die mit allen neu abgezweigten Unterprozessen exportiert werden sollen."
categories: "common"
---
> Weitere Informationen: <https://www.gnu.org/software/bash/manual/bash.html#index-export>.

- Lege eine neue Umgebungsvariable fest:

```bash
export variable=wert
```

- Entferne eine Umgebungsvariable:

```bash
export -n variable
```

- Markiere eine Shell-Funktion für den Export:

```bash
export -f funktionsname
```

- Hänge etwas an die PATH-Variable an:

```bash
export PATH=$PATH:pfad/zu/anhängen
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[S-Espinet](mailto:91517918+S-Espinet@users.noreply.github.com) | export: add German translation (#7341) | 2021-11-03T14:38:09 | [c75bb8d7657f](https://github.com/tldr-pages/tldr/commit/c75bb8d7657faf486da78e903f669ada3e70a4b9)


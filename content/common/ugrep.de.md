---
author: ['Dr. Robert van Engelen']
date: 1656269315
title: "ugrep"
description: "ugrep, Ultraschnelles Suchtool mit Abfrage-TUI."
categories: "common"
---
> Weitere Informationen: <https://github.com/Genivia/ugrep>.

- Starte eine interaktive TUI um rekursiv nach Dateien im aktuellen Verzeichnis zu suchen (Strg-Z für Hilfe):

```bash
ugrep --query
```

- Suche im aktuellen Verzeichnis rekursiv nach Dateien, die einem bestimmten regulären Ausdruck entsprechen:

```bash
ugrep "suchmuster"
```

- Suche in einer Datei oder in allen Dateien in einem bestimmten Verzeichnis und zeige die Zeilennummer jedes Treffers:

```bash
ugrep --line-number "suchmuster" pfad/zu/datei_oder_verzeichnis
```

- Suche in allen Dateien im aktuellen Verzeichnis rekursiv und zeige den Dateinamen jeder passenden Datei:

```bash
ugrep --files-with-matches "suchmuster"
```

- Suche nach einem "fuzzy" regulären Ausdruck mit bis zu 3 zusätzlichen, fehlenden oder nicht übereinstimmenden Zeichen:

```bash
ugrep --fuzzy=3 "suchmuster"
```

- Suche auch in allen komprimierten Dateien und `zip`- und `tar`-Archive:

```bash
ugrep --decompress "suchmuster"
```

- Suche nur in Dateien deren Dateinamen mit einem bestimmten glob-Muster übereinstimmen:

```bash
ugrep --glob="glob_muster" "suchmuster"
```

- Suche nur in C++ Quelldateien (verwende `--file-type=list`, um mögliche Optionen aufzulisten):

```bash
ugrep --file-type=cpp "suchmuster"
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Dr. Robert van Engelen](mailto:genivia-inc@users.noreply.github.com) | ugrep: add page (#7972) | 2022-06-26T20:48:35 | [803e0814a61d](https://github.com/tldr-pages/tldr/commit/803e0814a61d3661a582e7afda749c8c4f4e333a)


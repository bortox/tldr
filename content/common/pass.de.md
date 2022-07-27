---
author: ['b3nj4m1n', 'marchersimon', 'lucas schneider']
date: 1619262596
title: "pass, TLDR Pages"
description: "pass, Programm zum Speichern und Lesen von Passwörtern und anderen sensiblen Daten."
categories: "common"
---
> Die Daten sind mit GPG verschlüsselt und werden mit einem Git repository verwaltet.

> Weitere Informationen: <https://www.passwordstore.org>.

- Initialisiere oder verschlüssle einen neuen oder bestehenden Speicher mit einer oder mehreren GPG IDs neu:

```bash
pass init gpg_id_1 gpg_id_2
```

- Speichere das Passwort und zusätzliche Informationen (Str + D auf neuer Zeile zum abschließen):

```bash
pass insert --multiline pfad/zu/datei
```

- Bearbeite einen bestimmten Eintrag:

```bash
pass edit pfad/zu/datei
```

- Kopiere das Passwort (die erste Zeile des Eintrags) in die Zwischenablage:

```bash
pass -c pfad/zu/datei
```

- Zeige die Baumstruktur des Passwort-Stores an:

```bash
pass
```

- Generiere ein neues, zufälliges Passwort mit Länge n und kopiere is in die Zwischenablage:

```bash
pass generate -c pfad/zu/datei n
```

- Initialisiere ein Git Repository (Alle durch pass durchgeführten Änderungen werden automatisch committed):

```bash
pass git init
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[b3nj4m1n](mailto:b3nj4m1n@gmx.net) | pass: add German translation | 2020-07-02T17:41:08 | [a628b624a1be](https://github.com/tldr-pages/tldr/commit/a628b624a1bea98fa2ab279393e356bc56980cd6)


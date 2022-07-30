---
author: ['SKANKHUNTER', 'marchersimon']
date: 1619262596
title: "csvsql"
description: "csvsql, Generiere SQL-Anweisungen für eine CSV-Datei oder führe diese Anweisungen direkt in einer Datenbank aus."
categories: "common"
---
> Teil von csvkit.

> Weitere Informationen: <https://csvkit.readthedocs.io/en/latest/scripts/csvsql.html>.

- Generiere eine `CREATE TABLE`-SQL-Anweisung für eine CSV-Datei:

```bash
csvsql pfad/zu/datei.csv
```

- Importiere eine CSV-Datei in eine SQL-Datenbank:

```bash
csvsql --insert --db "mysql://benutzer:passwort@host/datenbank" pfad/zu/datei.csv
```

- Führe eine SQL-Abfrage auf einer CSV-Datei aus:

```bash
csvsql --query "select * from 'datei'" datei.csv
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[SKANKHUNTER](mailto:31552675+MrBurrBurr@users.noreply.github.com) | csvsql: add German translation (#4561) | 2020-10-09T00:27:46 | [cc4dcf7d3b85](https://github.com/tldr-pages/tldr/commit/cc4dcf7d3b85f3c00c23634a801e3634d0f182b1)


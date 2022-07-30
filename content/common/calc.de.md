---
author: ['marchersimon']
date: 1658004747
title: "calc"
description: "calc, Ein interaktiver Rechner im Terminal mit beliebiger Genauigkeit."
categories: "common"
---
> Weitere Informationen: <https://github.com/lcn2/calc>.

- Starte `calc` im interaktiven Modus:

```bash
calc
```

- Führe eine nicht-interaktive Berechnung durch:

```bash
calc '85 * (36 / 4)'
```

- Führe eine Berechnung durch ohne die Ausgabe zu formatieren (für das Benutzen mit Pipes):

```bash
calc -p '4/3 * pi() * 5^3'
```

- Führe eine Berechnung durch und wechsle dann in den [i]nteraktiven Modus:

```bash
calc -i 'sqrt(2)'
```

- Starte `calc` in einem bestimmten Berechtigungs[m]odus (0 bis 7, standardmäßig 7):

```bash
calc -m mode
```

- Öffne eine Einführung zu `calc`:

```bash
calc help intro
```

- Öffne eine Übersicht von `calc`:

```bash
calc help overview
```

- Öffne die Bedienungsanleitung von `calc`:

```bash
calc help
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | calc: set help example as lastest example (#8149) | 2022-07-16T22:52:27 | [0039248eb45e](https://github.com/tldr-pages/tldr/commit/0039248eb45ef45c6958e46670eea043225f83e4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | calc: move from `linux` to `common` (#8148) | 2022-06-25T07:10:35 | [829a51b02447](https://github.com/tldr-pages/tldr/commit/829a51b024474aa484e033c7707f84058a5166e3)


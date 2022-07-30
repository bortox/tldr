---
author: ['Joachim Schwarm']
date: 1633119495
title: "nodemon"
description: "nodemon, Beobachtet Dateien und startet Node Applikationen automatisch neu, wenn Änderungen erkannt wurden."
categories: "common"
---
> Weitere Informationen: <https://nodemon.io>.

- Führe die angegebene Datei aus und warte auf Änderungen:

```bash
nodemon pfad/zu/datei.js
```

- Manueller Neustart von Nodemon (beachte, dass Nodemon dabei aktiv sein muss):

```bash
rs
```

- Ignoriere bestimmte Dateien:

```bash
nodemon --ignore pfad/zu/datei_oder_verzeichnis
```

- Übergib Argumente an die Node Applikation:

```bash
nodemon pfad/zu/datei.js argumente
```

- Führe Nicht-Node Skripte aus:

```bash
nodemon --exec "python --verbose" pfad/zu/datei.py
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | nodemon: add German translation (#6636) | 2021-10-01T22:18:15 | [0e63317f8f4a](https://github.com/tldr-pages/tldr/commit/0e63317f8f4a8e604bac828a796cbac33f3dcb2c)


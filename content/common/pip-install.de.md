---
author: ['Daniel']
date: 1633293301
title: "pip install, TLDR Pages"
description: "pip install, Installiere Python-Pakete."
categories: "common"
---
> Weitere Informationen: <https://pip.pypa.io>.

- Installiere ein Paket:

```bash
pip install paketname
```

- Installiere eine spezifische Paketversion:

```bash
pip install paketname==paketversion
```

- Installiere die Pakete aus einer Datei:

```bash
pip install -r requirements.txt
```

- Installiere die Pakete von einer URL oder einem lokalen Archiv (.tar.gz | .whl):

```bash
pip install -f url|pfad/zur/datei
```

- Installiere das lokale Paket im aktuellen Verzeichnis im Entwicklungs-/Bearbeitungsmodus:

```bash
pip install -e .
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:33197631+dadav@users.noreply.github.com) | pip-install: add German translation (#6691) | 2021-10-03T22:35:01 | [a21d8ebe6ed9](https://github.com/tldr-pages/tldr/commit/a21d8ebe6ed988e6fb0e813aa6f3662448112e43)


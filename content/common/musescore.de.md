---
author: ['marchersimon', 'Daniel']
date: 1634914980
title: "musescore, TLDR Pages"
description: "musescore, MuseScore 3 Notenblatt-Editor."
categories: "common"
---
> Weitere Informationen: <https://musescore.org/en/handbook/3/command-line-options>.

- Verwende einen bestimmten Audio-Treiber:

```bash
musescore --audio-driver jack|alsa|portaudio|pulse
```

- Setze die MP3 Output-Bitrate in kbit/s:

```bash
musescore --bitrate bitrate
```

- Starte MuseScore im Debug-Modus:

```bash
musescore --debug
```

- Aktiviere experimentelle Funktionen, wie Layer:

```bash
musescore --experimental
```

- Exportiere eine Datei in ein anderes Format. Dieses hängt von der Dateierweiterung ab:

```bash
musescore --export-to output_datei input_datei
```

- Zeige Unterschiede zwischen zwei Partituren:

```bash
musescore --diff pfad/zu/datei1 pfad/zu/datei2
```

- Gib eine MIDI-Importoperationsdatei an:

```bash
musescore --midi-operations pfad/zu/datei
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | musescore: add German translation (#6234) | 2021-07-18T12:00:00 | [e62b8f05ad3c](https://github.com/tldr-pages/tldr/commit/e62b8f05ad3cb0ebe17e4ae5bb8687d2b383194f)


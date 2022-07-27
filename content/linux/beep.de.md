---
author: ['Anja Elzinger']
date: 1634201302
title: "beep, TLDR Pages"
description: "beep, Ein Befehl, um den PC-Lautsprecher zu steuern."
categories: "linux"
---
> Weitere Informationen: <https://github.com/spkr-beep/beep>.

- Gib einen Ton aus:

```bash
beep
```

- Gib einen Ton mehrmals aus:

```bash
beep -r wiederholungen
```

- Gib einen Ton mit einer bestimmten Frequenz (Hz) und Länge (Millisekunden) aus:

```bash
beep -f frequenz -l länge
```

- Spiele jede neue Frequenz und Länge als einen eigenen Ton:

```bash
beep -f frequenz -l länge -n -f frequenz -l länge
```

- Spiele die C-Dur-Tonleiter:

```bash
beep -f 262 -n -f 294 -n -f 330 -n -f 349 -n -f 392 -n -f 440 -n -f 494 -n -f 523
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Anja Elzinger](mailto:35960947+entensee403@users.noreply.github.com) | beep: add German translation (#6939) | 2021-10-14T10:48:22 | [6c5fe7692586](https://github.com/tldr-pages/tldr/commit/6c5fe7692586c9913e3b490efffc5011764ccadc)


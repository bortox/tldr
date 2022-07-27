---
author: ['Paradact']
date: 1635464542
title: "musescore, TLDR Pages"
description: "musescore, MuseScore 3 bladmuziek bewerker."
categories: "common"
---
> Meer informatie: <https://musescore.org/en/handbook/3/command-line-options>.

- Gebruik een specifiek audio stuurprogramma:

```bash
musescore --audio-driver jack|alsa|portaudio|pulse
```

- Stel de MP3 uitvoer bitsnelheid in in kbit/s:

```bash
musescore --bitrate bitsnelheid
```

- Open MuseScore in debug modus:

```bash
musescore --debug
```

- Schakel experimentele funcies in, bijvoorbeeld lagen:

```bash
musescore --experimental
```

- Exporteer het gegeven bestand naar het gegeven uitvoer bestand. Het bestandstype hangt af van de gegeven extentie:

```bash
musescore --export-to uitvoer_bestand invoer_bestand
```

- Geef het verschil tussen de gegeven partituren:

```bash
musescore --diff pad/naar/bestand1 pad/naar/bestand2
```

- Specificeer een MIDI invoer operaties bestand:

```bash
musescore --midi-operations pad/naar/bestand
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[Paradact](mailto:44441385+Paradact@users.noreply.github.com) | musescore, mscore: add Dutch translation (#7253) Co-authored-by: CleanMachine1 <78213164+CleanMachine1@users.noreply.github.com> | 2021-10-29T01:42:22 | [f28ae0118173](https://github.com/tldr-pages/tldr/commit/f28ae0118173be8c85f8a21e929fcd9a869f035c)


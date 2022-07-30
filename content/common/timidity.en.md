---
author: ['CleanMachine1', 'Daniil Baturin']
date: 1656619054
title: "timidity"
description: "timidity, TiMidity++ is a MIDI file player and converter."
categories: "common"
---
> More information: <http://timidity.sourceforge.net>.

- Play a MIDI file:

```bash
timidity path/to/file.mid
```

- Play a MIDI file in a loop:

```bash
timidity --loop path/to/file.mid
```

- Play a MIDI file in a specific key (0 = C major/A minor, -1 = F major/D minor, +1 = G major/E minor, etc.):

```bash
timidity --force-keysig=-flats|+sharps path/to/file.mid
```

- Convert a MIDI file to PCM (WAV) audio:

```bash
timidity --output-mode=w --output-file=path/to/file.wav path/to/file.mid
```

- Convert a MIDI file to FLAC audio:

```bash
timidity --output-mode=F --output-file=path/to/file.flac path/to/file.mid
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | Fix spelling mistakes | 2022-06-30T21:57:34 | [a0828299099a](https://github.com/tldr-pages/tldr/commit/a0828299099a2224eca625dcf412c341124c5011)
[Daniil Baturin](mailto:daniil@vyos.io) | timidity: add page (#6908) | 2021-10-10T16:44:10 | [af8db122b755](https://github.com/tldr-pages/tldr/commit/af8db122b755062d47c1943b3f9d392521955d38)


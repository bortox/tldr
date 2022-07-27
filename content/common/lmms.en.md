---
author: ['Gingka Akiyama', 'bl-ue']
date: 1621541621
title: "lmms, TLDR Pages"
description: "lmms, Free, open source, cross-platform digital audio workstation."
categories: "common"
---
> Render a `.mmp` or `.mmpz` project file, dump a `.mmpz` as XML, or start the GUI.

> More information: <https://lmms.io>.

- Start the GUI:

```bash
lmms
```

- Start the GUI and load external config:

```bash
lmms --config path/to/config.xml
```

- Start the GUI and import MIDI or Hydrogen file:

```bash
lmms --import path/to/midi/or/hydrogen/file
```

- Start the GUI with a specified window size:

```bash
lmms --geometry x_sizexy_size+x_offset+y_offset
```

- Dump a `.mmpz` file:

```bash
lmms dump path/to/mmpz/file.mmpz
```

- Render a project file:

```bash
lmms render path/to/mmpz_or_mmp/file
```

- Render the individual tracks of a project file:

```bash
lmms rendertracks path/to/mmpz_or_mmp/file path/to/dump/directory
```

- Render with custom samplerate, format, and as a loop:

```bash
lmms render --samplerate 88200 --format ogg --loop --output path/to/output/file.ogg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Gingka Akiyama](mailto:33764485+GingkathFox@users.noreply.github.com) | lmms, SafeEjectGPU: add pages (#5163) * Add SafeEjectGPU and lmms * Well then * Add SafeEjectGPU and lmms * Update SafeEjectGPU and [...] | 2021-01-22T03:18:51 | [12ed2e119aa6](https://github.com/tldr-pages/tldr/commit/12ed2e119aa6482adeeee0fb5d32e7682f3c0269)


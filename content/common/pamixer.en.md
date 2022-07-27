---
author: ['Marco Bonelli', 'Alexander']
date: 1559564381
title: "pamixer, TLDR Pages"
description: "pamixer, A simple command-line mixer for PulseAudio."
categories: "common"
---
> More information: <https://github.com/cdemoulins/pamixer>.

- List all sinks and sources with their corresponding IDs:

```bash
pamixer --list-sinks --list-sources
```

- Set the volume to 75% on the default sink:

```bash
pamixer --set-volume 75
```

- Toggle mute on a sink other than the default:

```bash
pamixer --toggle-mute --sink ID
```

- Increase the volume on default sink by 5%:

```bash
pamixer --increase 5
```

- Decrease the volume on a source by 5%:

```bash
pamixer --decrease 5 --source ID
```

- Use the allow boost option to increase, decrease, or set the volume above 100%:

```bash
pamixer --set-volume 105 --allow-boost
```

- Mute the default sink (use `--unmute` instead to unmute):

```bash
pamixer --mute
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Alexander](mailto:2683344+terminalnode@users.noreply.github.com) | pamixer: add page (#2987) | 2019-05-09T22:57:30 | [a3d28e575f28](https://github.com/tldr-pages/tldr/commit/a3d28e575f28909dfe70aad98311be643f4f6a0f)


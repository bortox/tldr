---
author: ['Raffaele Mignone', 'bl-ue']
date: 1621541621
title: "khal"
description: "khal, A text-based calendar and scheduling application for the command-line."
categories: "common"
---
> More information: <https://lostpackets.de/khal>.

- Start khal on interactive mode:

```bash
ikhal
```

- Print all events scheduled in personal calendar for the next seven days:

```bash
khal list -a personal today 7d
```

- Print all events scheduled not in personal calendar for tomorrow at 10:00:

```bash
khal at -d personal tomorrow 10:00
```

- Print a calendar with a list of events for the next three months:

```bash
khal calendar
```

- Add new event to personal calendar:

```bash
khal new -a personal 2020-09-08 18:00 18:30 "Dentist appointment"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Raffaele Mignone](mailto:github@norangeb.it) | khal: add page (#4386) | 2020-10-01T13:04:16 | [94326fe32685](https://github.com/tldr-pages/tldr/commit/94326fe32685f2cd8c5a78236d55285871d0b55e)


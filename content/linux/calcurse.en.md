---
author: ['bl-ue', 'Fabio Bianchi', 'Marco Bonelli']
date: 1621541621
title: "calcurse"
description: "calcurse, A text-based calendar and scheduling application for the command-line."
categories: "linux"
---
> More information: <https://calcurse.org>.

- Start calcurse on interactive mode:

```bash
calcurse
```

- Print the appointments and events for the current day and exit:

```bash
calcurse --appointment
```

- Remove all local calcurse items and import remote objects:

```bash
calcurse-caldav --init=keep-remote
```

- Remove all remote objects and push local calcurse items:

```bash
calcurse-caldav --init=keep-local
```

- Copy local objects to the CalDAV server and vice versa:

```bash
calcurse-caldav --init=two-way
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Fabio Bianchi](mailto:13044134+fabiobianchiwebdev@users.noreply.github.com) | calcurse: add page (#2995) | 2019-05-24T22:32:45 | [9dafa0dee117](https://github.com/tldr-pages/tldr/commit/9dafa0dee117b25164cb6f6425de7936f8a01c2f)


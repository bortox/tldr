---
author: ['bl-ue', 'marchersimon']
date: 1621541621
title: "pio project, TLDR Pages"
description: "pio project, Tool to manage PlatformIO projects."
categories: "common"
---
> More information: <https://docs.platformio.org/en/latest/core/userguide/project/>.

- Initialize a new PlatformIO project:

```bash
pio project init
```

- Initialize a new PlatformIO project in a specific directory:

```bash
pio project init --project-dir path/to/project_directory
```

- Initialize a new PlatformIO project, specifying a board ID:

```bash
pio project init --board ATmega328P|uno|...
```

- Initialize a new PlatformIO based project, specifying one or more project options:

```bash
pio project init --project-option="option=value" --project-option="option=value"
```

- Print the configuration of a project:

```bash
pio project config
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:marchersimon@zohomail.eu) | remove index.html from more information links where posible | 2021-04-11T17:29:10 | [1e2f4f202a9e](https://github.com/tldr-pages/tldr/commit/1e2f4f202a9e7827b670bd2db5d1cb776316df06)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pio-project: add page (#5408) | 2021-03-25T00:49:47 | [b6421d95e011](https://github.com/tldr-pages/tldr/commit/b6421d95e011af07f157c45a36b2f26bd4e96a8f)


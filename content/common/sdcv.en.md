---
author: ['258204', 'Sailesh Shrestha', 'marchersimon']
date: 1637875968
title: "sdcv, TLDR Pages"
description: "sdcv, StarDict, a command-line dictionary client."
categories: "common"
---
> Dictionaries are provided separately from the client.

> More information: <https://manned.org/sdcv>.

- Start sdcv interactively:

```bash
sdcv
```

- List installed dictionaries:

```bash
sdcv --list-dicts
```

- Display a definition from a specific dictionary:

```bash
sdcv --use-dict dictionary_name search_term
```

- Look up a definition with a fuzzy search:

```bash
sdcv search_term
```

- Look up a definition with an exact search:

```bash
sdcv --exact-search search_term
```

- Look up a definition and format the output as JSON:

```bash
sdcv --json search_term
```

- Search for dictionaries in a specific directory:

```bash
sdcv --data-dir path/to/directory search_term
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sailesh Shrestha](mailto:34860977+werewolf-65@users.noreply.github.com) | sdcv, visudo: add link and --version example (#7207) | 2021-11-25T22:32:48 | [61c0ac06d84f](https://github.com/tldr-pages/tldr/commit/61c0ac06d84fa1984a72793c04ff5017df99c802)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | sdcv: fix spelling error (#6206) | 2021-07-09T06:40:08 | [0888fabbd07f](https://github.com/tldr-pages/tldr/commit/0888fabbd07f279af6c729b15b38350e3838b45c)
[258204](mailto:71364336+258204@users.noreply.github.com) | sdcv: add page (#6145) | 2021-07-07T21:33:01 | [6b8fdbee8e92](https://github.com/tldr-pages/tldr/commit/6b8fdbee8e926ca7a844a0401e50fc2539c60ba7)


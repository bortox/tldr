---
author: ['JohannesPertl']
date: 1640387386
title: "abbr, TLDR Pages"
description: "abbr, Manage abbreviations for the fish shell."
categories: "linux"
---
> User-defined words are replaced with longer phrases after they are entered.

> More information: <https://fishshell.com/docs/current/cmds/abbr.html>.

- Add a new abbreviation:

```bash
abbr --add abbreviation_name command command_arguments
```

- Rename an existing abbreviation:

```bash
abbr --rename old_name new_name
```

- Erase an existing abbreviation:

```bash
abbr --erase abbreviation_name
```

- Import the abbreviations defined on another host over SSH:

```bash
ssh host_name abbr --show | source
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[JohannesPertl](mailto:johannes.pertl@edu.fh-joanneum.at) | abbr: add page (#7508) | 2021-12-25T00:09:46 | [3d89af60cdcb](https://github.com/tldr-pages/tldr/commit/3d89af60cdcb9daaf020ea7cdf9f1b7cf630559b)


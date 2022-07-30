---
author: ['vlfldr']
date: 1655812838
title: "tmsu"
description: "tmsu, Simple command-line tool for tagging files."
categories: "common"
---
> More information: <https://tmsu.org>.

- Tag a specific file with multiple tags:

```bash
tmsu tag path/to/file.mp3 music big-jazz mp3
```

- Tag multiple files:

```bash
tmsu tag --tags "music mp3" *.mp3
```

- List tags of specified file(s):

```bash
tmsu tags *.mp3
```

- List files with specified tag(s):

```bash
tmsu files big-jazz music
```

- List files with tags matching boolean expression:

```bash
tmsu files "(year >= 1990 and year <= 2000) and grunge"
```

- Mount tmsu virtual filesystem to an existing directory:

```bash
tmsu mount path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[vlfldr](mailto:91982627+vlfldr@users.noreply.github.com) | tmsu: add page (#8132) | 2022-06-21T14:00:38 | [61231d32249f](https://github.com/tldr-pages/tldr/commit/61231d32249f304db109326a5a644010c07235bf)


---
author: ['Oliver Gerlich']
date: 1630035915
title: "ts, TLDR Pages"
description: "ts, Add timestamps to every line from standard input."
categories: "common"
---
> More information: <https://joeyh.name/code/moreutils/>.

- Add a timestamp to the beginning of each line:

```bash
some_command | ts
```

- Add timestamps with microsecond precision:

```bash
some_command | ts "%b %d %H:%M:%.S"
```

- Add [i]ncremental timestamps with microsecond precision, starting from zero:

```bash
some_command | ts -i "%H:%M:%.S"
```

- Convert existing timestamps in a text file (eg. a log file) into [r]elative format:

```bash
cat path/to/file | ts -r
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Oliver Gerlich](mailto:oliver.gerlich@gmx.de) | ts: add page (#6389) Co-authored-by: Muhammad Falak R Wani <falakreyaz@gmail.com> Co-authored-by: marchersimon [...] | 2021-08-27T05:45:15 | [8223d2df17b9](https://github.com/tldr-pages/tldr/commit/8223d2df17b9ea7ccb1305c65381a886f5debcc0)


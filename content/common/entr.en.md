---
author: ['Paul Garaud', 'marchersimon']
date: 1618869951
title: "entr, TLDR Pages"
description: "entr, Run arbitrary commands when files change."
categories: "common"
---
> More information: <https://manned.org/entr>.

- Rebuild with `make` if any file in any subdirectory changes:

```bash
ag -l | entr make
```

- Rebuild and test with `make` if any `.c` source files in the current directory change:

```bash
ls *.c | entr 'make && make test'
```

- Send a `SIGTERM` to any previously spawned ruby subprocesses before executing `ruby main.rb`:

```bash
ls *.rb | entr -r ruby main.rb
```

- Run a command with the changed file (`/_`) as an argument:

```bash
ls *.sql | entr psql -f /_
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Paul Garaud](mailto:circld@users.noreply.github.com) | entr: move to common (#3152) | 2019-07-01T00:22:46 | [334bb3c5fb06](https://github.com/tldr-pages/tldr/commit/334bb3c5fb06c80aa31185bfbba6f16cf39b2368)


---
author: ['Ruben Vereecken', 'Denis Sokolov', 'Emily Grace Seville', 'marchersimon']
date: 1644919136
title: "for"
description: "for, Perform a command several times."
categories: "common"
---
> More information: <https://www.gnu.org/software/bash/manual/bash.html#Looping-Constructs>.

- Execute the given commands for each of the specified items:

```bash
for variable in item1 item2 ...; do echo "Loop is executed"; done
```

- Iterate over a given range of numbers:

```bash
for variable in {from..to..step}; do echo "Loop is executed"; done
```

- Iterate over a given list of files:

```bash
for variable in path/to/file1 path/to/file2 ...; do echo "Loop is executed"; done
```

- Iterate over a given list of directories:

```bash
for variable in path/to/directory1/ path/to/directory2/ ...; do echo "Loop is executed"; done
```

- Perform a given command in every directory:

```bash
for variable in */; do (cd "$variable" || continue; echo "Loop is executed") done
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | for: refresh (#7482) | 2022-02-15T10:58:56 | [50a970825028](https://github.com/tldr-pages/tldr/commit/50a970825028e74e0a849e98d1d9b2f7dde7da10)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | for: add link (#5536) | 2021-03-30T09:26:00 | [209eddc19449](https://github.com/tldr-pages/tldr/commit/209eddc1944939b6650544058bc32d4fe24b64af)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Reformatted pages once more | 2016-01-13T12:04:46 | [967633411984](https://github.com/tldr-pages/tldr/commit/9676334119847078e5e05fec393a3fe36991dbc2)
[Denis Sokolov](mailto:denis@sokolov.cc) | for/if/while: add | 2016-01-07T16:40:49 | [27cc01819f77](https://github.com/tldr-pages/tldr/commit/27cc01819f7703b54ddf368990b96ea105d1e18a)


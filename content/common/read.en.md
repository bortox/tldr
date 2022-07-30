---
author: ['Cvetomir Denchev', 'Fallstar', 'Francesco Pira', 'Cvetomird91', 'Guido Lena Cota', 'laeccan', 'Orestis Floros', 'Sadeed']
date: 1634106170
title: "read"
description: "read, BASH builtin for retrieving data from standard input."
categories: "common"
---
> More information: <https://manned.org/read.1p>.

- Store data that you type from the keyboard:

```bash
read variable
```

- Store each of the next lines you enter as values of an array:

```bash
read -a array
```

- Specify the number of maximum characters to be read:

```bash
read -n character_count variable
```

- Use a specific character as a delimiter instead of a new line:

```bash
read -d new_delimiter variable
```

- Do not let backslash (\) act as an escape character:

```bash
read -r variable
```

- Display a prompt before the input:

```bash
read -p "Enter your input here: " variable
```

- Do not echo typed characters (silent mode):

```bash
read -s variable
```

- Read stdin and perform an action on every line:

```bash
while read line; do echo "$line"; done
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sadeed](mailto:sadeeedw@gmail.com) | rar, read, renice, rev, roll, route, rsync: add link (#6929) | 2021-10-13T08:22:50 | [6583ef2421da](https://github.com/tldr-pages/tldr/commit/6583ef2421da704fdb94b1acb67c70936ccb5ddf)
[Orestis Floros](mailto:orestisflo@gmail.com) | read: add example using 'while' (#5258) Copied from `while` As discussed in #5258, this replaces a less useful example to maintain the [...] | 2021-02-13T21:03:16 | [0155fb60babf](https://github.com/tldr-pages/tldr/commit/0155fb60babf4f1016647e33161c750cfa2b3c47)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[laeccan](mailto:laeccan@users.noreply.github.com) | read: Add parameter for reading input silently (#2731) | 2019-01-27T01:10:00 | [95d51a4306d6](https://github.com/tldr-pages/tldr/commit/95d51a4306d60fd77b1f3c7035e4601b3ae5bee8)
[Fallstar](mailto:gdstroumph@hotmail.fr) | read: add -p option (#2724) * read: add -p option | 2019-01-23T14:37:43 | [9c4f5869ebc0](https://github.com/tldr-pages/tldr/commit/9c4f5869ebc041629904407c8ff06763a014b27a)
[Francesco Pira](mailto:dev@fpira.com) | read: add -r option (#1702) | 2017-11-29T10:05:52 | [c173466f8eef](https://github.com/tldr-pages/tldr/commit/c173466f8eefac253f023ac1a0630103bb89b9ab)
[Cvetomir Denchev](mailto:cvetomir_denchev@abv.bg) | added accidentally removed line | 2016-01-27T09:19:21 | [f28c653143a9](https://github.com/tldr-pages/tldr/commit/f28c653143a91ad21ffe59b6c8cf07df750f2107)
[Cvetomir Denchev](mailto:cvetomir_denchev@abv.bg) | removed unnecessary lines | 2016-01-26T17:05:09 | [b7b24ab6927f](https://github.com/tldr-pages/tldr/commit/b7b24ab6927fb2c61d5e5c96f5847495688b754c)
[Cvetomir Denchev](mailto:cvetomir_denchev@abv.bg) | added missing closing backticks | 2016-01-26T10:52:58 | [526bc1aaba50](https://github.com/tldr-pages/tldr/commit/526bc1aaba5092b25301acd320edb164867c4ea4)
[Cvetomir Denchev](mailto:cvetomir_denchev@abv.bg) | removed git symbols | 2016-01-26T10:50:08 | [b0d9304892b8](https://github.com/tldr-pages/tldr/commit/b0d9304892b8e3972ab51dcc99ac3781090e3dff)
[Cvetomir Denchev](mailto:cvetomir_denchev@abv.bg) | removed git symbols | 2016-01-26T10:46:05 | [e1ddb560fe08](https://github.com/tldr-pages/tldr/commit/e1ddb560fe08e0c224f01d75f737466722aee4ae)
[Cvetomir Denchev](mailto:cvetomir_denchev@abv.bg) | fixed conflict | 2016-01-26T10:43:58 | [f194b860d078](https://github.com/tldr-pages/tldr/commit/f194b860d078dfe3ef91f9e51faba6c84139bf3a)
[Cvetomird91](mailto:cvetomirdenchev@gmail.com) | added a page for the read builtin | 2016-01-26T10:40:56 | [9547f8992c1d](https://github.com/tldr-pages/tldr/commit/9547f8992c1d7751381e91d3807a1e4c4bf27bdb)
[Cvetomird91](mailto:cvetomirdenchev@gmail.com) | added a page for the read builtin | 2016-01-05T22:47:20 | [fd0bcd16816a](https://github.com/tldr-pages/tldr/commit/fd0bcd16816af623482a28042bded704fc203620)


---
author: ['pxgamer', 'Nev Delap']
date: 1559676580
title: "ned"
description: "ned, Is like `grep` but with powerful replace capabilities."
categories: "common"
---
> Unlike `sed`, as it isn't restricted to line oriented editing.

> More information: <https://github.com/nevdelap/ned>.

- Recursively search starting in the current directory, ignoring case:

```bash
ned --ignore-case --recursive '^[dl]og' .
```

- Search always showing colored output:

```bash
ned --colors '^[dl]og' .
```

- Search never showing colored output:

```bash
ned --colors=never '^[dl]og' .
```

- Search ignoring certain files:

```bash
ned --recursive --exclude '*.htm' '^[dl]og' .
```

- Simple replace:

```bash
ned 'dog' --replace 'cat' .
```

- Replace using numbered group references:

```bash
ned 'the ([a-z]+) dog and the ([a-z]+) dog' --replace 'the $2 dog and the $1 dog' .
```

- Replace changing case:

```bash
ned '([a-z]+) dog' --case-replacements --replace '\U$1\E! dog' --stdout .
```

- Preview results of a find and replace without updating the target files:

```bash
ned '^[sb]ad' --replace 'happy' --stdout .
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | ned: add link to homepage | 2019-06-04T21:29:40 | [ea0c5f354d41](https://github.com/tldr-pages/tldr/commit/ea0c5f354d41687c9468e57144ea36a61f42197d)
[Nev Delap](mailto:nevdelap@gmail.com) | ned: add page (#2787) | 2019-02-21T09:44:54 | [c0f1360e9927](https://github.com/tldr-pages/tldr/commit/c0f1360e9927f98dadbd77b4d8fce9bd75480568)


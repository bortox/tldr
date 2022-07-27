---
author: ['bl-ue', 'Starbeamrainbowlabs']
date: 1607722048
title: "reflac, TLDR Pages"
description: "reflac, Recompress FLAC files in-place while preserving metadata."
categories: "common"
---
> More information: <https://github.com/chungy/reflac>.

- Recompress a directory of FLAC files:

```bash
reflac path/to/directory
```

- Enable maximum compression (very slow):

```bash
reflac --best path/to/directory
```

- Display filenames as they are processed:

```bash
reflac --verbose path/to/directory
```

- Recurse into subdirectories:

```bash
reflac --recursive path/to/directory
```

- Preserve file modification times:

```bash
reflac --preserve path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | reflac: add page | 2020-03-02T04:27:26 | [6a93d4470ae6](https://github.com/tldr-pages/tldr/commit/6a93d4470ae6c26ff409c8d628298a86900d63ac)


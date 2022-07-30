---
author: ['W. M. Moreland', 'Seth Falco']
date: 1656325392
title: "unison"
description: "unison, Bidirectional file synchronisation tool."
categories: "common"
---
> More information: <https://www.cis.upenn.edu/~bcpierce/unison/download/releases/stable/unison-manual.html>.

- Sync two directories (creates log first time these two directories are synchronized):

```bash
unison path/to/directory_1 path/to/directory_2
```

- Automatically accept the (non-conflicting) defaults:

```bash
unison path/to/directory_1 path/to/directory_2 -auto
```

- Ignore some files using a pattern:

```bash
unison path/to/directory_1 path/to/directory_2 -ignore pattern
```

- Show documentation:

```bash
unison -doc topics
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[W. M. Moreland](mailto:wmoreland@pm.me) | unison: add page (#3358) | 2019-10-08T19:46:12 | [c1e257fd44dc](https://github.com/tldr-pages/tldr/commit/c1e257fd44dc7c83b08253955363b7f2463df2ab)


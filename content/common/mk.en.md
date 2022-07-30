---
author: ['pixel']
date: 1645094863
title: "mk"
description: "mk, Task runner for targets described in Mkfile."
categories: "common"
---
> Mostly used to control the compilation of an executable from source code.

> More information: <http://doc.cat-v.org/plan_9/4th_edition/papers/mk>.

- Call the first target specified in the Mkfile (usually named "all"):

```bash
mk
```

- Call a specific target:

```bash
mk target
```

- Call a specific target, executing 4 jobs at a time in parallel:

```bash
NPROC=4 mk target
```

- Force mking of a target, even if source files are unchanged:

```bash
mk -wtarget target
```

- Assume all targets to be out of date. Thus, update `target` and all of its dependencies:

```bash
mk -a target
```

- Keep going as far as possible on error:

```bash
mk -k
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | mk: add page (#7756) | 2022-02-17T11:47:43 | [60413b149c60](https://github.com/tldr-pages/tldr/commit/60413b149c601cb704d84f789c09169789ec7edc)


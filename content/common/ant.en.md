---
author: ['siavashsoleymani', 'Karthikeyan Vaithilingam']
date: 1603796471
title: "ant"
description: "ant, Apache Ant."
categories: "common"
---
> Tool for building and managing Java-based projects.

> More information: <https://ant.apache.org>.

- Build a project with default build file `build.xml`:

```bash
ant
```

- Build a project using build file other than `build.xml`:

```bash
ant -f buildfile.xml
```

- Print information on possible targets for this project:

```bash
ant -p
```

- Print debugging information:

```bash
ant -d
```

- Execute all targets that do not depend on fail target(s):

```bash
ant -k
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[siavashsoleymani](mailto:siavash.solimanii@yahoo.com) | ant: fix typo | 2020-10-27T12:01:11 | [04f2a99002ff](https://github.com/tldr-pages/tldr/commit/04f2a99002ff7e5681af47055dc8cad100a2d0e6)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | ant: add page (#4153) | 2020-07-06T17:57:49 | [7c8ffa3e1548](https://github.com/tldr-pages/tldr/commit/7c8ffa3e1548ac63543a69aa59b7e716f64c8277)


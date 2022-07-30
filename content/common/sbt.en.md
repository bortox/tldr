---
author: ['pixel', 'Elijah Shackelford', 'Natechawin Suthison', 'marchersimon']
date: 1633627733
title: "sbt"
description: "sbt, Build tool for Scala and Java projects."
categories: "common"
---
> More information: <https://www.scala-sbt.org/1.x/docs/>.

- Start a REPL (interactive shell):

```bash
sbt
```

- Create a new Scala project from an existing Giter8 template hosted on GitHub:

```bash
sbt new scala/hello-world.g8
```

- Compile and run all tests:

```bash
sbt test
```

- Delete all generated files in the `target` directory:

```bash
sbt clean
```

- Compile the main sources in `src/main/scala` and `src/main/java` directories:

```bash
sbt compile
```

- Use the specified version of sbt:

```bash
sbt -sbt-version version
```

- Use a specific jar file as the sbt launcher:

```bash
sbt -sbt-jar path
```

- List all sbt options:

```bash
sbt -h
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Elijah Shackelford](mailto:33649649+eshack94@users.noreply.github.com) | sbt: add test example (#6739) | 2021-10-07T19:28:53 | [f0cf3e3a922b](https://github.com/tldr-pages/tldr/commit/f0cf3e3a922b1926a533e1fa6afc4435533630f9)
[Elijah Shackelford](mailto:33649649+eshack94@users.noreply.github.com) | sbt: add compile example (#6738) | 2021-10-05T05:10:22 | [46e9678b3b0b](https://github.com/tldr-pages/tldr/commit/46e9678b3b0b79ca65c1729ddf6e439f5e7187c0)
[Elijah Shackelford](mailto:33649649+eshack94@users.noreply.github.com) | sbt: add clean example (#6639) | 2021-10-04T21:41:27 | [0387d6143cba](https://github.com/tldr-pages/tldr/commit/0387d6143cbafec46ec80897ba56945961ccf9a3)
[pixel](mailto:35269695+pixelcmtd@users.noreply.github.com) | pages/common/*.md: REPL Normalization (#6471) | 2021-09-12T16:03:27 | [882781e41019](https://github.com/tldr-pages/tldr/commit/882781e41019543fd716442e62faa1fb02d474b9)
[marchersimon](mailto:marchersimon@zohomail.eu) | remove index.html from more information links where posible | 2021-04-11T17:29:10 | [1e2f4f202a9e](https://github.com/tldr-pages/tldr/commit/1e2f4f202a9e7827b670bd2db5d1cb776316df06)
[Natechawin Suthison](mailto:natechawin@gmail.com) | sbt: add new project from template example (#3494) | 2019-11-04T21:00:57 | [aa64dc0f5514](https://github.com/tldr-pages/tldr/commit/aa64dc0f551478aca9127c943481c64d65c57182)
[Natechawin Suthison](mailto:natechawin@gmail.com) | sbt: add page (#3299) | 2019-10-04T08:50:39 | [088cb7913a6d](https://github.com/tldr-pages/tldr/commit/088cb7913a6dce3e315818dd0ea97d113a7ca620)


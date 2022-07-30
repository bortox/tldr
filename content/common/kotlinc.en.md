---
author: ['Howard Yun']
date: 1634500912
title: "kotlinc"
description: "kotlinc, Kotlin compiler."
categories: "common"
---
> More information: <https://kotlinlang.org/docs/command-line.html>.

- Start a REPL (interactive shell):

```bash
kotlinc
```

- Compile a Kotlin file:

```bash
kotlinc path/to/file.kt
```

- Compile several Kotlin files:

```bash
kotlinc path/to/file1.kt path/to/file2.kt ...
```

- Execute a specific Kotlin Script file:

```bash
kotlinc -script path/to/file.kts
```

- Compile a Kotlin file into a self contained jar file with the Kotlin runtime library included:

```bash
kotlinc path/to/file.kt -include-runtime -d path/to/file.jar
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Howard Yun](mailto:Haoy2001@gmail.com) | kotlinc: add page (#7006) | 2021-10-17T22:01:52 | [2f00e0732e1c](https://github.com/tldr-pages/tldr/commit/2f00e0732e1ca32b3bd8d6b3b350c781ace4fa40)


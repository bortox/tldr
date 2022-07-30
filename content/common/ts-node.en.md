---
author: ['Axel Navarro', 'SpiderMath']
date: 1643827401
title: "ts-node"
description: "ts-node, Run TypeScript code directly, without any compiling."
categories: "common"
---
> More information: <https://typestrong.org/ts-node>.

- Execute a TypeScript file without compiling (`node` + `tsc`):

```bash
ts-node path/to/file.ts
```

- Execute a TypeScript file without loading `tsconfig.json`:

```bash
ts-node --skip-project path/to/file.ts
```

- Evaluate TypeScript code passed as a literal on the command-line:

```bash
ts-node --eval 'console.log("Hello World")'
```

- Execute a TypeScript file in script mode:

```bash
ts-node --script-mode path/to/file.ts
```

- Transpile a TypeScript file to JavaScript without executing it:

```bash
ts-node --transpile-only path/to/file.ts
```

- Display TS-Node help:

```bash
ts-node --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | *: use author link instead of npm package (#7730) | 2022-02-02T19:43:21 | [c2c16f61acbd](https://github.com/tldr-pages/tldr/commit/c2c16f61acbdca1933961fbbc20a80bdae76ece5)
[SpiderMath](mailto:71999854+SpiderMath@users.noreply.github.com) | ts-node: add page (#5911) | 2021-05-12T19:06:54 | [4416b0df9d8d](https://github.com/tldr-pages/tldr/commit/4416b0df9d8de4180168f49d44ae92898982159c)


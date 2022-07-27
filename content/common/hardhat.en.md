---
author: ['Owen Voke']
date: 1633466272
title: "hardhat, TLDR Pages"
description: "hardhat, A development environment for Ethereum software."
categories: "common"
---
> More information: <https://hardhat.org>.

- List available subcommands (or create a new project if no configuration exists):

```bash
hardhat
```

- Compile the current project and build all artifacts:

```bash
hardhat compile
```

- Run a user-defined script after compiling the project:

```bash
hardhat run path/to/script.js
```

- Run Mocha tests:

```bash
hardhat test
```

- Run all given test files:

```bash
hardhat test path/to/file1.js path/to/file2.js
```

- Start a local Ethereum JSON-RPC node for development:

```bash
hardhat node
```

- Start a local Ethereum JSON-RPC node with a specific hostname and port:

```bash
hardhat node --hostname hostname --port port
```

- Clean the cache and all artifacts:

```bash
hardhat clean
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | hardhat: add page (#6627) | 2021-10-05T22:37:52 | [51238e5abeb7](https://github.com/tldr-pages/tldr/commit/51238e5abeb77cba881d18b911dcdf44bd48dd6a)


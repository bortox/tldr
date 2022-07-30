---
author: ['Axel Navarro']
date: 1631458566
title: "corepack"
description: "corepack, Zero-runtime-dependency package acting as bridge between Node projects and their package managers."
categories: "common"
---
> More information: <https://github.com/nodejs/corepack>.

- Add the Corepack shims to the Node.js installation directory to make them available as global commands:

```bash
corepack enable
```

- Add the Corepack shims to a specific directory:

```bash
corepack enable --install-directory path/to/directory
```

- Remove the Corepack shims from the Node.js installation directory:

```bash
corepack disable
```

- Prepare a specific package manager:

```bash
corepack prepare package_manager@version --activate
```

- Prepare the package manager configured for the project in the current path:

```bash
corepack prepare
```

- Use a package manager without installing it as a global command:

```bash
corepack npm|pnpm|yarn package_manager_arguments
```

- Install a package manager from the specified archive:

```bash
corepack hydrate path/to/corepack.tgz
```

- Display help for a subcommand:

```bash
corepack subcommand --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | corepack: add page (#6485) | 2021-09-12T16:56:06 | [972c9425085b](https://github.com/tldr-pages/tldr/commit/972c9425085b8e71d8f959b10b933adc6cb7e8ee)


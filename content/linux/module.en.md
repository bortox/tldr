---
author: ['Alberto Mario Ceballos-Arroyo', 'Caughlin Bohn']
date: 1633975483
title: "module"
description: "module, Modify a users' environment using the module command."
categories: "linux"
---
> More information: <https://lmod.readthedocs.io/en/latest/010_user.html>.

- Display available modules:

```bash
module avail
```

- Search for a module by name:

```bash
module avail module_name
```

- Load a module:

```bash
module load module_name
```

- Display loaded modules:

```bash
module list
```

- Unload a specific loaded module:

```bash
module unload module_name
```

- Unload all loaded modules:

```bash
module purge
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alberto Mario Ceballos-Arroyo](mailto:alceballosa@unal.edu.co) | module: fix bug in examples (#6954) | 2021-10-11T20:04:43 | [2365635c1538](https://github.com/tldr-pages/tldr/commit/2365635c15386cb579e70768cc6ab5fafe7751dc)
[Caughlin Bohn](mailto:35080828+cbohn4@users.noreply.github.com) | module: add page (#4628) | 2020-10-13T12:54:38 | [3097a8c50e4e](https://github.com/tldr-pages/tldr/commit/3097a8c50e4ea0706caf3ab9adf0b3cfe08f2cad)


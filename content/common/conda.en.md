---
author: ['Schneider', 'Marco Bonelli', 'Phil Ewels', 'Hervé Nivon', 'marchersimon']
date: 1631521281
title: "conda, TLDR Pages"
description: "conda, Package, dependency and environment management for any programming language."
categories: "common"
---
> Some subcommands such as `conda create` have their own usage documentation.

> More information: <https://github.com/conda/conda>.

- Create a new environment, installing named packages into it:

```bash
conda create --name environment_name python=3.9 matplotlib
```

- List all environments:

```bash
conda info --envs
```

- Load an environment:

```bash
conda activate environment_name
```

- Unload an environment:

```bash
conda deactivate
```

- Delete an environment (remove all packages):

```bash
conda remove --name environment_name --all
```

- Install packages into the current environment:

```bash
conda install python=3.4 numpy
```

- List currently installed packages in current environment:

```bash
conda list
```

- Delete unused packages and caches:

```bash
conda clean --all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Hervé Nivon](mailto:herve.nivon@gmail.com) | conda: fix examples (#6050) | 2021-05-27T23:23:56 | [528727f70fa9](https://github.com/tldr-pages/tldr/commit/528727f70fa9d57b148ff8850068afdaedb96cd0)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | conda.md: add homepage | 2019-05-04T15:48:27 | [9e2e9ecb812b](https://github.com/tldr-pages/tldr/commit/9e2e9ecb812b85ea4e7c8fe9d556238c9d123859)
[Hervé Nivon](mailto:herve.nivon@gmail.com) | `source deactivate` is deprecated (#2827) | 2019-03-12T12:57:08 | [a66920ebcf3e](https://github.com/tldr-pages/tldr/commit/a66920ebcf3e4c0cf1a74945381c347f6b80bb24)
[Phil Ewels](mailto:phil.ewels@scilifelab.se) | conda: add page (#1158) | 2016-11-29T10:14:38 | [fffe42cf5dff](https://github.com/tldr-pages/tldr/commit/fffe42cf5dffe358fc7be6580b87916dba7e7ba7)


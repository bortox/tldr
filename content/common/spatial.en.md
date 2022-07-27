---
author: ['Andrea Della Corte', 'Andrea']
date: 1511814615
title: "spatial, TLDR Pages"
description: "spatial, A set of commands for managing and developing SpatialOS projects."
categories: "common"
---
- Run this when you use a project for the first time:

```bash
spatial worker build
```

- Build workers for local deployment on Unity on macOS:

```bash
spatial worker build --target=development --target=Osx
```

- Build workers for local deployment on Unreal on Windows:

```bash
spatial worker build --target=local --target=Windows
```

- Deploy locally:

```bash
spatial local launch launch_config --snapshot=snapshot_file
```

- Launch a local worker to connect to your local deployment:

```bash
spatial local worker launch worker_type launch_config
```

- Upload an assembly to use for cloud deployments:

```bash
spatial cloud upload assembly_name
```

- Launch a cloud deployment:

```bash
spatial cloud launch assembly_name launch_config deployment_name
```

- Clean worker directories:

```bash
spatial worker clean
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Andrea](mailto:andrea@dellacorte.me) | spatial: fix macOS command | 2017-11-27T21:30:15 | [e953129676fe](https://github.com/tldr-pages/tldr/commit/e953129676feb85c66907c12f31ecc3447328cb6)
[Andrea](mailto:andrea@dellacorte.me) | spatial: add clean and build, address review comments | 2017-11-26T11:21:02 | [5902534b0ccc](https://github.com/tldr-pages/tldr/commit/5902534b0cccaa48c5d1a8dd6e42e1d7f16ea815)
[Andrea Della Corte](mailto:andrea@dellacorte.me) | spatial: add page | 2017-11-24T15:07:30 | [3610a3204fda](https://github.com/tldr-pages/tldr/commit/3610a3204fdad2f6e3f5357bc6fe3d7102fe38a3)


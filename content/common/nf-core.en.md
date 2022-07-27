---
author: ['Alexander Peltzer']
date: 1568967749
title: "nf-core, TLDR Pages"
description: "nf-core, The nf-core framework tools, to create, check and develop best-practice guidelines for Nextflow."
categories: "common"
---
> More information: <https://nf-co.re/tools>.

- List existing pipelines on nf-core:

```bash
nf-core list
```

- Create a new pipeline skeleton:

```bash
nf-core create
```

- Lint the pipeline code:

```bash
nf-core lint path/to/directory
```

- Bump software versions in pipeline recipe:

```bash
nf-core bump-version path/to/directory new_version
```

- Launch an nf-core pipeline:

```bash
nf-core launch pipeline_name
```

- Download an nf-core pipeline for offline use:

```bash
nf-core download pipeline_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alexander Peltzer](mailto:apeltzer@users.noreply.github.com) | nf-core: add page (#3274) | 2019-09-20T10:22:29 | [f3bb4d677a29](https://github.com/tldr-pages/tldr/commit/f3bb4d677a29a350c5d0dd6d9cc07d86d59badd7)


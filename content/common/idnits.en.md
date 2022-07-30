---
author: ['bl-ue']
date: 1622154566
title: "idnits"
description: "idnits, Check internet-drafts for submission nits."
categories: "common"
---
> Looks for violations of Section 2.1 and 2.2 of the requirements listed on <https://www.ietf.org/id-info/checklist>.

> More information: <https://tools.ietf.org/tools/idnits/>.

- Check a file for nits:

```bash
idnits path/to/file.txt
```

- Count nits without displaying them:

```bash
idnits --nitcount path/to/file.txt
```

- Show extra information about offending lines:

```bash
idnits --verbose path/to/file.txt
```

- Expect the specified year in the boilerplate instead of the current year:

```bash
idnits --year 2021 path/to/file.txt
```

- Assume the document is of the specified status:

```bash
idnits --doctype standard|informational|experimental|bcp|ps|ds path/to/file.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | idnits: add page (#6000) | 2021-05-28T00:29:26 | [f53c6b87f96a](https://github.com/tldr-pages/tldr/commit/f53c6b87f96acafce5698da5ad1b45cfd6f82cee)


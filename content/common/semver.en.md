---
author: ['Pierre Rudloff']
date: 1634056458
title: "semver"
description: "semver, Semantic version string parser."
categories: "common"
---
> More information: <https://github.com/npm/node-semver>.

- Check if a version string respects the semantic versioning format (prints an empty string if it does not match):

```bash
semver 1.2
```

- Convert a version string to the semantic versioning format:

```bash
semver --coerce 1.2
```

- Test if `1.2.3` matches the `^1.0` range (prints an empty string if it does not match):

```bash
semver 1.2.3 --range "^1.0"
```

- Test with multiple ranges:

```bash
semver 1.2.3 --range ">=1.0" "<2.0"
```

- Test multiple version strings and return only the ones that match:

```bash
semver 1.2.3 2.0.0 --range "^1.0"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | semver: add page (#6936) | 2021-10-12T18:34:18 | [a25d38a97a47](https://github.com/tldr-pages/tldr/commit/a25d38a97a4734950363bb596e214c9d59f6e155)


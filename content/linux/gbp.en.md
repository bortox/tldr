---
author: ['Emanuele Rocca']
date: 1636451181
title: "gbp"
description: "gbp, A system to integrate the Debian package build system with Git."
categories: "linux"
---
> More information: <http://honk.sigxcpu.org/projects/git-buildpackage/manual-html/gbp.html>.

- Convert an existing Debian package to gbp:

```bash
gbp import-dsc path/to/package.dsc
```

- Build the package in the current directory using the default builder (`debuild`):

```bash
gbp buildpackage -jauto -us -uc
```

- Build a package in a `pbuilder` environment for Debian Bullseye:

```bash
DIST=bullseye ARCH=amd64 gbp buildpackage -jauto -us -uc --git-builder=git-pbuilder
```

- Specify a package to be a source-only upload in the `.changes` file (see https://wiki.debian.org/SourceOnlyUpload):

```bash
gbp buildpackage -jauto -us -uc --changes-options=-S
```

- Import a new upstream release:

```bash
gbp import-orig --pristine-tar path/to/package.tar.gz
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emanuele Rocca](mailto:ema@linux.it) | gbp: add page (#7216) | 2021-11-09T10:46:21 | [6ec0551a5237](https://github.com/tldr-pages/tldr/commit/6ec0551a52378a5c8beed08a246e842df45660e7)


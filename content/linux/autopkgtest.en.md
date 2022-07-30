---
author: ['Emanuele Rocca']
date: 1638104229
title: "autopkgtest"
description: "autopkgtest, Run tests on Debian packages."
categories: "linux"
---
> More information: <https://wiki.debian.org/ContinuousIntegration/autopkgtest>.

- Build the package in the current directory and run all tests directly on the system:

```bash
autopkgtest -- null
```

- Run a specific test for the package in the current directory:

```bash
autopkgtest --test-name=test_name -- null
```

- Download and build a specific package with `apt-get`, then run all tests:

```bash
autopkgtest package -- null
```

- Test the package in the current directory using a new root directory:

```bash
autopkgtest -- chroot path/to/new/root
```

- Test the package in the current directory without rebuilding it:

```bash
autopkgtest --no-built-binaries -- null
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emanuele Rocca](mailto:ema@linux.it) | autopkgtest: add page (#7220) | 2021-11-28T13:57:09 | [3d5e9fe47549](https://github.com/tldr-pages/tldr/commit/3d5e9fe4754970e678db795f671d2f9f6a8c134d)


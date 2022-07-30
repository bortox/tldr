---
author: ['Seth Falco']
date: 1648039436
title: "laptop-detect"
description: "laptop-detect, Attempt to determine if the script is running on a laptop or desktop."
categories: "linux"
---
> More information: <https://gitlab.com/debiants/laptop-detect>.

- Return an exit status of 0 if the current device is likely a laptop, else returns 1:

```bash
laptop-detect
```

- Print the type of device that the current system is detected as:

```bash
laptop-detect --verbose
```

- Display the version:

```bash
laptop-detect --version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | laptop-detect: add page (#7919) | 2022-03-23T13:43:56 | [3184f70e6fa4](https://github.com/tldr-pages/tldr/commit/3184f70e6fa4469b683dc2b9aa0ded05ad9b6f9a)


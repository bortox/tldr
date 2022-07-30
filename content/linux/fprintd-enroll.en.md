---
author: ['Axel Navarro']
date: 1635805484
title: "fprintd-enroll"
description: "fprintd-enroll, Enroll fingerprints into the database."
categories: "linux"
---
> More information: <https://manned.org/fprintd-enroll>.

- Enroll the right index finger for the current user:

```bash
fprintd-enroll
```

- Enroll a specific finger for the current user:

```bash
fprintd-enroll --finger left-thumb|left-index-finger|left-middle-finger|left-ring-finger|left-little-finger|right-thumb|right-index-finger|right-middle-finger|right-ring-finger|right-little-finger
```

- Enroll the right index finger for a specific user:

```bash
fprintd-enroll username
```

- Enroll a specific finger for a specific user:

```bash
fprintd-enroll --finger finger_name username
```

- Display help:

```bash
fprintd-enroll --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | fprintd-enroll: add page (#7181) | 2021-11-01T23:24:44 | [d3032663b140](https://github.com/tldr-pages/tldr/commit/d3032663b140dc49a7bcb54b7edf5b777840f717)


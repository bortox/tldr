---
author: ['Emily Grace Seville', 'Tim Phan']
date: 1644837703
title: "spctl"
description: "spctl, Manage the security assessment policy subsystem."
categories: "osx"
---
> Utility for managing Gatekeeper in macOS.

> More information: <https://www.unix.com/man-page/osx/8/SPCTL/>.

- Turn off Gatekeeper:

```bash
spctl --master-disable
```

- Add a rule to allow an application to run (labeling of rule is optional):

```bash
spctl --add --label rule_name path/to/file
```

- Turn on Gatekeeper:

```bash
spctl --master-enable
```

- List all rules on the system:

```bash
spctl --list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Tim Phan](mailto:timpania@hotmail.com) | spctl: add page (#7565) | 2021-12-22T11:26:13 | [753142839f9f](https://github.com/tldr-pages/tldr/commit/753142839f9fd020d0562ac55d3e350f47fa9582)


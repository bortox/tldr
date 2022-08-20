---
author: ['Florian B', 'CleanMachine1']
date: 1660955935
title: "Stormlock"
description: "Stormlock, Centralized locking system."
categories: "common"
---
> More information: <https://github.com/tmccombs/stormlock>.

- Acquire a lease for resource:

```bash
stormlock acquire resource
```

- Release the given lease for the given resource:

```bash
stormlock release resource lease_id
```

- Show information on the current lease for a resource, if any:

```bash
stormlock current resource
```

- Test if a lease for given resource is currently active:

```bash
stormlock is-held resource lease_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | *: fix spelling error | 2022-08-20T02:38:55 | [dc513e71927a](https://github.com/tldr-pages/tldr/commit/dc513e71927a6bd5c71ed08fcc95e353d71b0339)
[Florian B](mailto:gn0mish@protonmail.com) | stormlock: add page (#5751) | 2021-04-15T19:47:12 | [c2949ae95e4e](https://github.com/tldr-pages/tldr/commit/c2949ae95e4e159eb9ab90ec18cb80b392a35c4b)


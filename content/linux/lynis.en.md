---
author: ['Marco Bonelli', 'Starbeamrainbowlabs']
date: 1559564381
title: "lynis, TLDR Pages"
description: "lynis, System and security auditing tool."
categories: "linux"
---
> More information: <https://cisofy.com/documentation/lynis/>.

- Check that Lynis is up-to-date:

```bash
sudo lynis update info
```

- Run a security audit of the system:

```bash
sudo lynis audit system
```

- Run a security audit of a Dockerfile:

```bash
sudo lynis audit dockerfile path/to/dockerfile
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | lynis: add page (#3034) | 2019-05-16T18:54:20 | [bb1a320cfbeb](https://github.com/tldr-pages/tldr/commit/bb1a320cfbebf39d9b62f0abe369d4d5929d2ae1)


---
author: ['Azrael JD', 'Lucas Gabriel Schneider', 'Cvetomird91']
date: 1643292617
title: "sysctl"
description: "sysctl, List and change kernel runtime variables."
categories: "linux"
---
> More information: <https://manned.org/sysctl.8>.

- Show all available variables and their values:

```bash
sysctl -a
```

- Set a changeable kernel state variable:

```bash
sysctl -w section.tunable=value
```

- Get currently open file handlers:

```bash
sysctl fs.file-nr
```

- Get limit for simultaneous open files:

```bash
sysctl fs.file-max
```

- Apply changes from `/etc/sysctl.conf`:

```bash
sysctl -p
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Azrael JD](mailto:94840719+azraeljd@users.noreply.github.com) | sysctl: add more information link (#7718) | 2022-01-27T15:10:17 | [c837506fd7c3](https://github.com/tldr-pages/tldr/commit/c837506fd7c335137e6a42ceebe3a6eb3061caaa)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Cvetomird91](mailto:cvetomirdenchev@gmail.com) | added Linux version for sysctl | 2016-02-01T10:11:15 | [3ef7b4eeb22a](https://github.com/tldr-pages/tldr/commit/3ef7b4eeb22a7e6af6ce20f2243c4103d122fb04)


---
author: ['pixel', 'Miles Glapa-Grossklag']
date: 1630393071
title: "pfetch"
description: "pfetch, Display system information."
categories: "common"
---
> More information: <https://github.com/dylanaraps/pfetch>.

- Display the ASCII art and default fields:

```bash
pfetch
```

- Display only the ASCII art and color palette fields:

```bash
PF_INFO="ascii palette" pfetch
```

- Display all possible fields:

```bash
PF_INFO="ascii title os host kernel uptime pkgs memory shell editor wm de palette" pfetch
```

- Display a different username and hostname:

```bash
USER="user" HOSTNAME="hostname" pfetch
```

- Display without colors:

```bash
PF_COLOR=0 pfetch
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:35269695+pixelcmtd@users.noreply.github.com) | pfetch: add example for running with defaults (#6437) | 2021-08-31T08:57:51 | [2a71b87788cc](https://github.com/tldr-pages/tldr/commit/2a71b87788cc3b493b6e74dc015feecdc1c94d19)
[Miles Glapa-Grossklag](mailto:miles@glapa-grossklag.com) | pfetch: add page (#6414) | 2021-08-29T16:16:17 | [e67e49bb763a](https://github.com/tldr-pages/tldr/commit/e67e49bb763a6541c68647fda7ba7dfb8dc58e1f)


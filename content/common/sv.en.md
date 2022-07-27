---
author: ['Inesgor', 'marchersimon']
date: 1627153924
title: "sv, TLDR Pages"
description: "sv, Control a running runsv service."
categories: "common"
---
> More information: <https://manpages.ubuntu.com/manpages/latest/man8/sv.8.html>.

- Start a service:

```bash
sudo sv up path/to/service
```

- Stop a service:

```bash
sudo sv down path/to/service
```

- Get service status:

```bash
sudo sv status path/to/service
```

- Reload a service:

```bash
sudo sv reload path/to/service
```

- Start a service, but only if it's not running and don't restart it if it stops:

```bash
sudo sv once path/to/service
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Inesgor](mailto:81314876+Inesgor@users.noreply.github.com) | fc-pattern, sv, tomb, xkill: add examples (#6121) | 2021-07-24T21:12:04 | [3c2ddfbccca1](https://github.com/tldr-pages/tldr/commit/3c2ddfbccca1824d61550b57338503dd5572ccaa)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | runit, runsv, runsvdir, runsvchdir, sv: add more information link and move to common/ (#5648) | 2021-03-31T12:52:31 | [d562842e08a9](https://github.com/tldr-pages/tldr/commit/d562842e08a9fb8d1c71eb165394132acd5d9b3f)


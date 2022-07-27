---
author: ['Stig124', "Telmo 'Trooper"]
date: 1625841955
title: "amixer, TLDR Pages"
description: "amixer, Mixer for ALSA soundcard driver."
categories: "linux"
---
> More information: <https://manned.org/amixer>.

- Turn up the master volume by 10%:

```bash
amixer -D pulse sset Master 10%+
```

- Turn down the master volume by 10%:

```bash
amixer -D pulse sset Master 10%-
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Telmo 'Trooper](mailto:telmo.trooper@gmail.com) | amixer: add page (#2994) | 2019-05-09T18:23:59 | [ffd4aca8c507](https://github.com/tldr-pages/tldr/commit/ffd4aca8c507726115aacd51919bf79e67a57896)


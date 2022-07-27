---
author: ['Seth Falco', 'marchersimon', 'NikonP']
date: 1629050349
title: "aplay, TLDR Pages"
description: "aplay, Command-line sound player for ALSA soundcard driver."
categories: "linux"
---
> More information: <https://manned.org/aplay>.

- Play a specific file (sampling rate, bit depth, etc. will be automatically determined for the file format):

```bash
aplay path/to/file
```

- Play the first 10 seconds of a specific file at 2500 Hz:

```bash
aplay --duration=10 --rate=2500 path/to/file
```

- Play the raw file as a 22050 Hz, mono, 8-bit, Mu-Law `.au` file:

```bash
aplay --channels=1 --file-type raw --rate=22050 --format=mu_law path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[NikonP](mailto:podgorny.nikon@yandex.ru) | aplay: add page (#4591) | 2020-10-12T22:58:51 | [99b2c81f779b](https://github.com/tldr-pages/tldr/commit/99b2c81f779bf651e834e015bc0d2dba1584ee5d)


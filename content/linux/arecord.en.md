---
author: ['Florian Peter', 'Seth Falco', 'marchersimon', 'Ray Voice']
date: 1629050349
title: "arecord, TLDR Pages"
description: "arecord, Sound recorder for ALSA soundcard driver."
categories: "linux"
---
> More information: <https://manned.org/arecord>.

- Record a snippet in "CD" quality (finish with Ctrl-C when done):

```bash
arecord -vv --format=cd path/to/file.wav
```

- Record a snippet in "CD" quality, with a fixed duration of 10 seconds:

```bash
arecord -vv --format=cd --duration=10 path/to/file.wav
```

- Record a snippet and save it as an MP3 (finish with Ctrl-C when done):

```bash
arecord -vv --format=cd --file-type raw | lame -r - path/to/file.mp3
```

- List all sound cards and digital audio devices:

```bash
arecord --list-devices
```

- Allow interactive interface (e.g. use space-bar or enter to play or pause):

```bash
arecord --interactive
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[Ray Voice](mailto:33094591+Ray6464@users.noreply.github.com) | arecord: add example list audio devices and intractive interface (#4530) | 2020-10-12T23:28:39 | [1839fd6b6d21](https://github.com/tldr-pages/tldr/commit/1839fd6b6d213ab2df50d0d045c393e29c7105b9)
[Florian Peter](mailto:florian.peter@gmx.at) | arecord: add page (#4307) | 2020-09-09T01:56:16 | [6c405df7351a](https://github.com/tldr-pages/tldr/commit/6c405df7351a7ab272840970052db5286c455594)


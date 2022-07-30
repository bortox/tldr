---
author: ['Starbeamrainbowlabs', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "pulseaudio"
description: "pulseaudio, The PulseAudio sound system daemon and manager."
categories: "linux"
---
> More information: <https://www.freedesktop.org/wiki/Software/PulseAudio/>.

- Check if PulseAudio is running (a non-zero exit code means it is not running):

```bash
pulseaudio --check
```

- Start the PulseAudio daemon in the background:

```bash
pulseaudio --start
```

- Kill the running PulseAudio daemon:

```bash
pulseaudio --kill
```

- List available modules:

```bash
pulseaudio --dump-modules
```

- Load a module into the currently running daemon with the specified arguments:

```bash
pulseaudio --load="module_name arguments"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pulseaudio: add link (#6072) | 2021-05-31T14:05:19 | [89013d28a523](https://github.com/tldr-pages/tldr/commit/89013d28a5233cd765de215ea65b8a1bfd34ae29)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | pulseaudio: Add page | 2018-01-20T04:54:14 | [54b8408cc8bd](https://github.com/tldr-pages/tldr/commit/54b8408cc8bdd9dbb216e285ba349032ef4049d4)


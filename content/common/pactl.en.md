---
author: ['Alexander', 'Joshua Shanks']
date: 1633563243
title: "pactl"
description: "pactl, Control a running PulseAudio sound server."
categories: "common"
---
> More information: <https://manned.org/pactl>.

- List all sinks (or other types - sinks are outputs and sink-inputs are active audio streams):

```bash
pactl list sinks short
```

- Change the default sink (output) to 1 (the number can be retrieved via the `list` subcommand):

```bash
pactl set-default-sink 1
```

- Move sink-input 627 to sink 1:

```bash
pactl move-sink-input 627 1
```

- Set the volume of sink 1 to 75%:

```bash
pactl set-sink-volume 1 0.75
```

- Toggle mute on the default sink (using the special name `@DEFAULT_SINK@`):

```bash
pactl set-sink-mute @DEFAULT_SINK@ toggle
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Joshua Shanks](mailto:jjshanks@gmail.com) | nslookup, objdump, pactl, passwd, patch: add link (#6828) | 2021-10-07T01:34:03 | [d91120d92e31](https://github.com/tldr-pages/tldr/commit/d91120d92e31e12fa2bd5723fb386d9fe05438bf)
[Alexander](mailto:2683344+terminalnode@users.noreply.github.com) | pactl: add page (#2978) | 2019-05-09T09:47:21 | [0de48e85d481](https://github.com/tldr-pages/tldr/commit/0de48e85d48116993af7175c6e2b01f0ae2deec5)


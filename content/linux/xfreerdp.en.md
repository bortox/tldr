---
author: ['Fazle Arefin', 'HazemBZ', 'Lahfa Samy']
date: 1653390912
title: "xfreerdp"
description: "xfreerdp, Free Remote Desktop Protocol implementation."
categories: "linux"
---
> More information: <https://www.freerdp.com>.

- Connect to a FreeRDP server:

```bash
xfreerdp /u:username /p:password /v:ip_address
```

- Connect to a FreeRDP server and activate audio output redirection using `sys:alsa` device:

```bash
xfreerdp /u:username /p:password /v:ip_address /sound:sys:alsa
```

- Connect to a FreeRDP server with dynamic resolution:

```bash
xfreerdp /v:ip_address /u:username /p:password /dynamic-resolution
```

- Connect to a FreeRDP server with clipboard redirection:

```bash
xfreerdp /v:ip_address /u:username /p:password +clipboard
```

- Connect to a FreeRDP server ignoring any certificate checks:

```bash
xfreerdp /v:ip_address /u:username /p:password /cert:ignore
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Fazle Arefin](mailto:fazlearefin@users.noreply.github.com) | xfreerdp: add examples (#8096) | 2022-05-24T13:15:12 | [bd8c5082c719](https://github.com/tldr-pages/tldr/commit/bd8c5082c719b4baefe5a62b46fb6c5bf13e78b9)
[HazemBZ](mailto:hazem.benbouzaien@esprit.tn) | xfreerdp: add sound example (#7634) | 2022-01-10T06:25:40 | [a136aec12667](https://github.com/tldr-pages/tldr/commit/a136aec126676aa13e241ea8ec08390975e5185e)
[Lahfa Samy](mailto:samy@lahfa.xyz) | xfreerdp: add page (#7190) | 2021-10-25T01:16:19 | [13684a83be20](https://github.com/tldr-pages/tldr/commit/13684a83be20a1b8a5522681aecfe9ef421f9589)


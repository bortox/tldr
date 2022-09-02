---
author: ['Alexandre Hassan']
date: 1662058636
title: "gnmic get"
description: "gnmic get, Get a snapshot of a gnmi network device operation data."
categories: "common"
---
> More information: <https://gnmic.kmrd.dev/cmd/get>.

- Get a snapshot of the device state at a specific path:

```bash
gnmic --address ip:port get --path path
```

- Query the device state at multiple paths:

```bash
gnmic -a ip:port get --path path1 --path path2
```

- Query the device state at multiple paths with a common prefix:

```bash
gnmic -a ip:port get --prefix prefix --path path1 --path path2
```

- Query the device state and specify reponse encoding (json_ietf):

```bash
gnmic -a ip:port get --path path --encoding json_ietf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alexandre Hassan](mailto:alexhassan@live.ca) | gnmic: add page and subpages (#8367) * gnmic - add * Change file extension * Fix newlines * update gnmic pages and add gnmic sub alias [...] | 2022-09-01T20:57:16 | [ec300f80fa2d](https://github.com/tldr-pages/tldr/commit/ec300f80fa2d239ebf2a1b46afddc12468370506)


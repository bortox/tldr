---
author: ['Alexandre Hassan']
date: 1662058636
title: "gnmic"
description: "gnmic, A gNMI command-line client."
categories: "common"
---
> Manage gNMI network device configuration and view operational data.

> More information: <https://gnmic.kmrd.dev>.

- Request device capabilities:

```bash
gnmic --address ip:port capabilities
```

- Provide a username and password to fetch device capabilities:

```bash
gnmic --address ip:port --username username --password password capabilities
```

- Get a snapshot of the device state at a specific path:

```bash
gnmic -a ip:port get --path path
```

- Update device state at a specific path:

```bash
gnmic -a ip:port set --update-path path --update-value value
```

- Subscribe to target state updates under the subtree at a specific path:

```bash
gnmic -a ip:port subscribe --path path
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alexandre Hassan](mailto:alexhassan@live.ca) | gnmic: add page and subpages (#8367) * gnmic - add * Change file extension * Fix newlines * update gnmic pages and add gnmic sub alias [...] | 2022-09-01T20:57:16 | [ec300f80fa2d](https://github.com/tldr-pages/tldr/commit/ec300f80fa2d239ebf2a1b46afddc12468370506)


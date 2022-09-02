---
author: ['Alexandre Hassan']
date: 1662058636
title: "gnmic subscribe"
description: "gnmic subscribe, Subscribe to a gnmic network device state updates."
categories: "common"
---
> More information: <https://gnmic.kmrd.dev/cmd/subscribe>.

- Subscribe to target state updates under the subtree of a specific path:

```bash
gnmic --address ip:port subscribe --path path
```

- Subscribe to a target with a sample interval of 30s (default is 10s):

```bash
gnmic -a ip:port subscribe --path path --sample-interval 30s
```

- Subscribe to a target with sample interval and updates only on change:

```bash
gnmic -a ip:port subscribe --path path --stream-mode on-change --heartbeat-interval 1m
```

- Subscribe to a target for only one update:

```bash
gnmic -a ip:port subscribe --path path --mode once
```

- Subscribe to a target and specify reponse encoding (json_ietf):

```bash
gnmic -a ip:port subscribe --path path --encoding json_ietf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alexandre Hassan](mailto:alexhassan@live.ca) | gnmic: add page and subpages (#8367) * gnmic - add * Change file extension * Fix newlines * update gnmic pages and add gnmic sub alias [...] | 2022-09-01T20:57:16 | [ec300f80fa2d](https://github.com/tldr-pages/tldr/commit/ec300f80fa2d239ebf2a1b46afddc12468370506)


---
author: ['Peter Babič']
date: 1624998697
title: "lxi, TLDR Pages"
description: "lxi, Control LXI compatible instruments such as oscilloscopes."
categories: "linux"
---
> More information: <https://github.com/lxi-tools/lxi-tools>.

- Discover LXI devices on available networks:

```bash
lxi discover
```

- Capture a screenshot, detecting a plugin automatically:

```bash
lxi screenshot --address ip_address
```

- Capture a screenshot using a specified plugin:

```bash
lxi screenshot --address ip_address --plugin rigol-1000z
```

- Send an SCPI command to an instrument:

```bash
lxi scpi --address ip_address "*IDN?"
```

- Run a benchmark for request and response performance:

```bash
lxi benchmark --address ip_address
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Peter Babič](mailto:peter@babic.dev) | lxi: add page (#6174) | 2021-06-29T22:31:37 | [826b295394d9](https://github.com/tldr-pages/tldr/commit/826b295394d963975070f7d214613111926422b3)


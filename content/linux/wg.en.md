---
author: ['Managor', 'marcan2020', 'Muhammad Falak R Wani']
date: 1641204591
title: "wg"
description: "wg, Manage the configuration of WireGuard interfaces."
categories: "linux"
---
> More information: <https://www.wireguard.com/quickstart/>.

- Check status of currently active interfaces:

```bash
wg
```

- Generate a new private key:

```bash
wg genkey
```

- Generate a public key from a private key:

```bash
wg pubkey < path/to/private_key > path/to/public_key
```

- Generate a public and private key:

```bash
wg genkey | tee path/to/private_key | wg pubkey > path/to/public_key
```

- Show the current configuration of a wireguard interface:

```bash
wg showconf wg0
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | wg: add example to show current configuration of an interface (#7594) Signed-off-by: Muhammad Falak R Wani <falakreyaz@gmail.com> | 2022-01-03T11:09:51 | [722304b2162d](https://github.com/tldr-pages/tldr/commit/722304b2162d869d36c2d4b494944ff9d896dc89)
[marcan2020](mailto:marcan2020@gmail.com) | wg: refresh and add French translation (#6687) | 2021-10-14T05:24:01 | [50fad57fd18c](https://github.com/tldr-pages/tldr/commit/50fad57fd18cfb3efc92d41c69d66e8a649e382e)
[Managor](mailto:42655600+Managor@users.noreply.github.com) | wg, wg-quick: add page (#5260) | 2021-02-12T12:28:04 | [87f1e8a511ab](https://github.com/tldr-pages/tldr/commit/87f1e8a511ab9d9003e9ea136cd76ea55b87b5bc)


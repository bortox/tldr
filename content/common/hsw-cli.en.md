---
author: ['Axel Navarro', 'Owen Voke', 'bl-ue']
date: 1643827401
title: "hsw-cli"
description: "hsw-cli, The command-line REST tool for the Handshake wallet."
categories: "common"
---
> More information: <https://github.com/handshake-org/hs-client>.

- Unlock the current wallet (timeout in seconds):

```bash
hsw-cli unlock passphrase timeout
```

- Lock the current wallet:

```bash
hsw-cli lock
```

- View the current wallet's details:

```bash
hsw-cli get
```

- View the current wallet's balance:

```bash
hsw-cli balance
```

- View the current wallet's transaction history:

```bash
hsw-cli history
```

- Send a transaction with the specified coin amount to an address:

```bash
hsw-cli send address 1.05
```

- View the current wallet's pending transactions:

```bash
hsw-cli pending
```

- View details about a transaction:

```bash
hsw-cli tx transaction_hash
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | *: use author link instead of npm package (#7730) | 2022-02-02T19:43:21 | [c2c16f61acbd](https://github.com/tldr-pages/tldr/commit/c2c16f61acbdca1933961fbbc20a80bdae76ece5)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Owen Voke](mailto:owzie123@gmail.com) | hsw-cli: add page (#3110) | 2019-06-17T20:36:46 | [923d2dffeb93](https://github.com/tldr-pages/tldr/commit/923d2dffeb93c3c71e3507471c4ad3f0723c0bde)


---
author: ['Waldir Pimenta']
date: 1562539898
title: "bitcoin-cli, TLDR Pages"
description: "bitcoin-cli, Command-line client to interact with the Bitcoin daemon via RPC calls."
categories: "common"
---
> Uses the configuration defined in `bitcoin.conf`.

> More information: <https://en.bitcoin.it/wiki/Running_Bitcoin#Command-line_arguments>.

- Send a transaction to a given address:

```bash
bitcoin-cli sendtoaddress "address" amount
```

- Generate one or more blocks:

```bash
bitcoin-cli generate num_blocks
```

- Print high-level information about the wallet:

```bash
bitcoin-cli getwalletinfo
```

- List all outputs from previous transactions available to fund outgoing transactions:

```bash
bitcoin-cli listunspent
```

- Export the wallet information to a text file:

```bash
bitcoin-cli dumpwallet "path/to/file"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Waldir Pimenta](mailto:waldyrious@gmail.com) | bitcoin-cli: add page (#3174) | 2019-07-08T00:51:38 | [d4922ade0830](https://github.com/tldr-pages/tldr/commit/d4922ade083036e8febab0e02c843dc32ecc3c77)


---
author: ['Marco Bonelli', 'bl-ue', 'Owen Voke']
date: 1621541621
title: "hsd-cli, TLDR Pages"
description: "hsd-cli, The command-line REST tool for the Handshake blockchain."
categories: "common"
---
> More information: <https://handshake.org>.

- Retrieve information about the current server:

```bash
hsd-cli info
```

- Broadcast a local transaction:

```bash
hsd-cli broadcast transaction_hex
```

- Retrieve a mempool snapshot:

```bash
hsd-cli mempool
```

- View a transaction by address or hash:

```bash
hsd-cli tx address_or_hash
```

- View a coin by its hash index or address:

```bash
hsd-cli coin hash_index_or_address
```

- View a block by height or hash:

```bash
hsd-cli block height_or_hash
```

- Reset the chain to the specified block:

```bash
hsd-cli reset height_or_hash
```

- Execute an RPC command:

```bash
hsd-cli rpc command args
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | hsd-cli: add page (#2812) | 2019-03-12T14:49:11 | [381c6bf2bcb0](https://github.com/tldr-pages/tldr/commit/381c6bf2bcb0d20f34f4a9fb4b46a8647dbfd726)


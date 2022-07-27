---
author: ['Ruben Vereecken', 'Agniva De Sarker', 'pxgamer', 'rprieto']
date: 1560056064
title: "electrum, TLDR Pages"
description: "electrum, Ergonomic Bitcoin wallet and private key management."
categories: "common"
---
> More information: <https://electrum.org>.

- Create a new wallet:

```bash
electrum -w new_wallet.dat create
```

- Restore an existing wallet from seed offline:

```bash
electrum -w recovery_wallet.dat restore -o
```

- Create a signed transaction offline:

```bash
electrum mktx recipient amount -f 0.0000001 -F from -o
```

- Display all wallet receiving addresses:

```bash
electrum listaddresses -a
```

- Sign a message:

```bash
electrum signmessage address message
```

- Verify a message:

```bash
electrum verifymessage address signature message
```

- Connect only to a specific electrum-server instance:

```bash
electrum -p socks5:127.0.0.1:9050 -s 56ckl5obj37gypcu.onion:50001:t -1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | electrum: add link to homepage | 2019-06-09T06:54:24 | [9c646a048c0e](https://github.com/tldr-pages/tldr/commit/9c646a048c0e9029b2a653a741c3d43e5336f0ce)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)


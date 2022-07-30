---
author: ['MarloweW', 'Peter Tripp', 'Patrice Denis', 'Ruben Vereecken']
date: 1618665963
title: "apt-key"
description: "apt-key, Key management utility for the APT Package Manager on Debian and Ubuntu."
categories: "linux"
---
> Note: `apt-key` is now deprecated (except for the use of `apt-key del` in maintainer scripts).

> More information: <https://manpages.debian.org/latest/apt/apt-key.8.html>.

- List trusted keys:

```bash
apt-key list
```

- Add a key to the trusted keystore:

```bash
apt-key add public_key_file.asc
```

- Delete a key from the trusted keystore:

```bash
apt-key del key_id
```

- Add a remote key to the trusted keystore:

```bash
wget -qO - https://host.tld/filename.key | apt-key add -
```

- Add a key from keyserver with only key id:

```bash
apt-key adv --keyserver pgp.mit.edu --recv KEYID
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[MarloweW](mailto:MarloweW@users.noreply.github.com) | apt-key: add adv option (#1221) | 2017-01-03T10:40:24 | [13cbf55d4da1](https://github.com/tldr-pages/tldr/commit/13cbf55d4da1aae2d85fb739ba48577860cf43fe)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Fixed damage done by formatter some time ago | 2016-01-28T12:41:42 | [b4304e105004](https://github.com/tldr-pages/tldr/commit/b4304e1050045b410af4ac90f71a90aeb506de44)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Reformatted pages once more | 2016-01-13T12:04:46 | [967633411984](https://github.com/tldr-pages/tldr/commit/9676334119847078e5e05fec393a3fe36991dbc2)
[Peter Tripp](mailto:petertripp@gmail.com) | Add apt-key for managing system trusted GPG keys. | 2016-01-09T11:59:56 | [e660e79eb5f8](https://github.com/tldr-pages/tldr/commit/e660e79eb5f8913ecd6be186ded39a2737cc6341)


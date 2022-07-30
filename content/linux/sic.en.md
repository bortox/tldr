---
author: ['Florian B']
date: 1617818130
title: "sic"
description: "sic, Simple IRC client."
categories: "linux"
---
> Part of the suckless tools.

> More information: <https://tools.suckless.org/sic/>.

- Connect to the default host (irc.ofct.net) with the nickname set in the `$USER` environment variable:

```bash
sic
```

- Connect to a given host, using a given nickname:

```bash
sic -h host -n nickname
```

- Connect to a given host, using a given nickname and password:

```bash
sic -h host -n nickname -k password
```

- Join a channel:

```bash
:j #channel<Enter>
```

- Send a message to a channel or user:

```bash
:m #channel|user<Enter>
```

- Set default channel or user:

```bash
:s #channel|user<Enter>
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Florian B](mailto:gn0mish@protonmail.com) | sic: add page (#5694) | 2021-04-07T19:55:30 | [8830f2607606](https://github.com/tldr-pages/tldr/commit/8830f26076066f6b57e4e5986b88d9ac3ebf434d)


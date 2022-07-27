---
author: ['Axel Navarro']
date: 1643036613
title: "trust, TLDR Pages"
description: "trust, Tool for operating on the trust policy store."
categories: "linux"
---
> More information: <https://manned.org/trust>.

- List trust policy store items:

```bash
trust list
```

- List information about specific items in the trust policy store:

```bash
trust list --filter=blocklist|ca-anchors|certificates|trust-policy
```

- Store a specific trust anchor in the trust policy store:

```bash
trust anchor path/to/certificate.crt
```

- Remove a specific anchor from the trust policy store:

```bash
trust anchor --remove path/to/certificate.crt
```

- Extract trust policy from the shared trust policy store:

```bash
trust extract --format=x509-directory --filter=ca-anchors path/to/directory
```

- Display help for a subcommand:

```bash
trust subcommand --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | trust: add page (#7699) | 2022-01-24T16:03:33 | [6b9e9fc683f0](https://github.com/tldr-pages/tldr/commit/6b9e9fc683f0379016601a6d8f6738193f6bf8af)


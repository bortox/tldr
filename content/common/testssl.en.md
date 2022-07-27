---
author: ['Pierre Rudloff']
date: 1601731893
title: "testssl, TLDR Pages"
description: "testssl, Check SSL/TLS protocols and ciphers supported by a server."
categories: "common"
---
> More information: <https://testssl.sh/>.

- Test a server (run every check) on port 443:

```bash
testssl example.com
```

- Test a different port:

```bash
testssl example.com:465
```

- Only check available protocols:

```bash
testssl --protocols example.com
```

- Only check vulnerabilities:

```bash
testssl --vulnerable example.com
```

- Only check HTTP security headers:

```bash
testssl --headers example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | testssl: add page (#4424) | 2020-10-03T15:31:33 | [f36635c12f88](https://github.com/tldr-pages/tldr/commit/f36635c12f88ec7fa41e3e3cf2ed4164d82aec02)


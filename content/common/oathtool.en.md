---
author: ['Emily Grace Seville']
date: 1644837703
title: "oathtool, TLDR Pages"
description: "oathtool, OATH one-time password tool."
categories: "common"
---
> More information: <https://www.nongnu.org/oath-toolkit/oathtool.1.html>.

- Generate TOTP token (behaves like Google Authenticator):

```bash
oathtool --totp --base32 "secret"
```

- Generate a TOTP token for a specific time:

```bash
oathtool --totp --now "2004-02-29 16:21:42" --base32 "secret"
```

- Validate a TOTP token:

```bash
oathtool --totp --base32 "secret" "token"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)


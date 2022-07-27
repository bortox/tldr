---
author: ['Miles Glapa-Grossklag']
date: 1630037785
title: "paperkey, TLDR Pages"
description: "paperkey, An OpenPGP key archiver."
categories: "common"
---
> More information: <https://www.jabberwocky.com/software/paperkey/>.

- Take a specific secret key and generate a text file with the secret data:

```bash
paperkey --secret-key path/to/secret_key.gpg --output path/to/secret_data.txt
```

- Take the secret key data in `secret_data.txt` and combine it with the public key to reconstruct the secret key:

```bash
paperkey --pubring path/to/public_key.gpg --secrets path/to/secret_data.txt --output secret_key.gpg
```

- Export a specific secret key and generate a text file with the secret data:

```bash
gpg --export-secret-key key | paperkey --output path/to/secret_data.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Miles Glapa-Grossklag](mailto:miles@glapa-grossklag.com) | paperkey: add page (#6378) | 2021-08-27T06:16:25 | [09f9b04b4c79](https://github.com/tldr-pages/tldr/commit/09f9b04b4c79df3fc0f15d1e1816212fef5c0da8)


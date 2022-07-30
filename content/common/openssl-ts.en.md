---
author: ['Ox1080']
date: 1623931603
title: "openssl ts"
description: "openssl ts, OpenSSL command to generate and verify timestamps."
categories: "common"
---
> More information: <https://www.openssl.org/docs/manmaster/man1/openssl-ts.html>.

- Generate a SHA-512 timestamp request of a specific file and output to `file.tsq`:

```bash
openssl ts -query -data path/to/file -sha512 -out path/to/file.tsq
```

- Check the date and metadata of a specific timestamp response file:

```bash
openssl ts -reply -in path/to/file.tsr -text
```

- Verify a timestamp request file and a timestamp response file from the server with an SSL certificate file:

```bash
openssl ts -verify -in path/to/file.tsr -queryfile path/to/file.tsq -partial_chain -CAfile path/to/cert.pem
```

- Create a timestamp response for request using key and signing certificate and output it to `file.tsr`:

```bash
openssl ts -reply -queryfile path/to/file.tsq -inkey path/to/tsakey.pem -signer tsacert.pem -out path/to/file.tsr
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ox1080](mailto:22803939+0x1080@users.noreply.github.com) | openssl-ts: add page (#6125) | 2021-06-17T14:06:43 | [ea473db76953](https://github.com/tldr-pages/tldr/commit/ea473db769538035b19efbdfe317c01db2eae425)


---
author: ['Furkan']
date: 1634756728
title: "rekor-cli"
description: "rekor-cli, Immutable tamper resistant ledger of metadata generated within a software projects supply chain."
categories: "common"
---
> More information: <https://github.com/sigstore/rekor>.

- Upload an artifact to Rekor:

```bash
rekor-cli upload --artifact path/to/file.ext --signature path/to/file.ext.sig --pki-format=x509 --public-key=path/to/key.pub
```

- Get information regarding entries in the Transparency Log:

```bash
rekor-cli get --uuid=0e81b4d9299e2609e45b5c453a4c0e7820ac74e02c4935a8b830d104632fd2d1
```

- Search the Rekor index to find entries by Artifact:

```bash
rekor-cli search --artifact path/to/file.ext
```

- Search the Rekor index to find entries by a specific hash:

```bash
rekor-cli search --sha 6b86b273ff34fce19d6b804eff5a3f5747ada4eaa22f1d49c01e52ddb7875b4b
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Furkan](mailto:furkan.turkal@trendyol.com) | rekor-cli: add page | 2021-10-20T21:05:28 | [6a293453e238](https://github.com/tldr-pages/tldr/commit/6a293453e238450212cabaeb016990deafa7b9eb)


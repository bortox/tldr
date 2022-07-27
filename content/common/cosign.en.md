---
author: ['Furkan']
date: 1634756728
title: "cosign, TLDR Pages"
description: "cosign, Container Signing, Verification and Storage in an OCI registry."
categories: "common"
---
> More information: <https://github.com/sigstore/cosign>.

- Generate a key-pair:

```bash
cosign generate-key-pair
```

- Sign a container and store the signature in the registry:

```bash
cosign sign -key cosign.key image
```

- Sign a container image with a key pair stored in a Kubernetes secret:

```bash
cosign sign -key k8s://namespace/key image
```

- Sign a blob with a local key pair file:

```bash
cosign sign-blob --key cosign.key file
```

- Verify a container against a public key:

```bash
cosign verify -key cosign.pub image
```

- Verify images with a public key in a Dockerfile:

```bash
cosign dockerfile verify -key cosign.pub path/to/Dockerfile
```

- Verify an image with a public key stored in a Kubernetes secret:

```bash
cosign verify -key k8s://namespace/key image
```

- Copy a container image and its signatures:

```bash
cosign copy example.com/src:latest example.com/dest:latest
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Furkan](mailto:furkan.turkal@trendyol.com) | cosign: add page | 2021-10-20T21:05:28 | [e61d22674d84](https://github.com/tldr-pages/tldr/commit/e61d22674d84a177a3c6eafd3c714b2be8956c76)


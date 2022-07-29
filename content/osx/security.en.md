---
author: ['Axel Navarro', 'M B', 'Adrien Thebo']
date: 1658992060
title: "security, TLDR Pages"
description: "security, Administer keychains, keys, certificates and the Security framework."
categories: "osx"
---
> More information: <https://ss64.com/osx/security.html>.

- List all available keychains:

```bash
security list-keychains
```

- Delete a specific keychain:

```bash
security delete-keychain path/to/file.keychain
```

- Create a keychain:

```bash
security create-keychain -p password path/to/file.keychain
```

- Set a certificate to use with a website or [s]ervice by its [c]ommon name (fails if several certificates with the same common name exist):

```bash
security set-identity-preference -s URL|hostname|service -c "common_name" path/to/file.keychain
```

- Add a certificate from file to a [k]eychain (if -k isn't specified, the default keychain is used):

```bash
security add-certificates -k keychain.name path/to/cert.pem
```

- Add a CA certificate to the per-user Trust Settings:

```bash
security add-trusted-cert -k path/to/user-keychain.keychain-db path/to/ca-cert.pem
```

- Remove a CA certificate from the per-user Trust Settings:

```bash
security remove-trusted-cert path/to/ca-cert.pem
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adrien Thebo](mailto:adrien@lagrange-automation.io) | security: add trusted cert add/remove examples (#8250) | 2022-07-28T09:07:40 | [4a9b06e3a9ff](https://github.com/tldr-pages/tldr/commit/4a9b06e3a9ffa86742541911628c7a9e6aedc849)
[M B](mailto:85039141+m-bartlett@users.noreply.github.com) | security: add more examples (#6645) | 2021-10-04T16:37:47 | [da5d38acdde8](https://github.com/tldr-pages/tldr/commit/da5d38acdde842b1582c329ff06d353b98224202)
[Axel Navarro](mailto:navarroaxel@gmail.com) | security: add page (#5033) | 2020-12-19T20:23:51 | [841e17f89a89](https://github.com/tldr-pages/tldr/commit/841e17f89a893dac3cb704c905c6c51b98471953)


---
author: ['pixel', 'bl-ue', 'Starbeamrainbowlabs']
date: 1643706393
title: "sn"
description: "sn, Mono StrongName utility for signing and verifying IL assemblies."
categories: "common"
---
> More information: <https://manned.org/sn>.

- Generate a new StrongNaming key:

```bash
sn -k path/to/key.snk
```

- Re-sign an assembly with the specified private key:

```bash
sn -R path/to/assembly.dll path/to/key_pair.snk
```

- Show the public key of the private key that was used to sign an assembly:

```bash
sn -T path/to/assembly.exe
```

- Extract the public key to a file:

```bash
sn -e path/to/assembly.dll path/to/output.pub
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | socat, sn, slimrb, swig: add more information link (#7733) | 2022-02-01T10:06:33 | [2396c6d791e9](https://github.com/tldr-pages/tldr/commit/2396c6d791e95702a3320ea3b13337f4a34998ea)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | autopep8, openssl-req, safe, sn, lvm: fix typo (#5719) | 2021-04-10T21:30:31 | [25a8f14863c7](https://github.com/tldr-pages/tldr/commit/25a8f14863c70faee5373a70c5a1eca82322621e)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | sn: add page (#2744) | 2019-02-04T21:03:39 | [ebdcd3056636](https://github.com/tldr-pages/tldr/commit/ebdcd305663659e554054c6207a13fac6f835dc8)


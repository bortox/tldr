---
author: ['Andréia Bohner']
date: 1659378325
title: "csrutil"
description: "csrutil, Gerencia a configuração do System Integrity Protection (SIP)."
categories: "osx"
---
> Mais informações: <https://ss64.com/osx/csrutil.html>.

- Exibe o status do System Integrity Protection:

```bash
csrutil status
```

- Desabilita o System Integrity Protection:

```bash
csrutil disable
```

- Habilita o System Integrity Protection:

```bash
csrutil enable
```

- Exibe a lista de origens permitidas do NetBoot:

```bash
csrutil netboot list
```

- Adiciona um endereço IPv4 à lista de origens permitidas do NetBoot:

```bash
csrutil netboot add endereço_ip
```

- Reseta o status do System Integrity Protection e limpa a lista do NetBoot:

```bash
csrutil clear
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Andréia Bohner](mailto:andreiabohner@gmail.com) | osx/*: add pt_BR translations (#8269) | 2022-08-01T20:25:25 | [97b386939aa5](https://github.com/tldr-pages/tldr/commit/97b386939aa505be651794a55d3bea20b4f14ab2)


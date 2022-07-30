---
author: ['gkah']
date: 1631104326
title: "arp-scan"
description: "arp-scan, Envia pacotes ARP para máquinas (identificadas por endereço IP ou por nome de domínio) em uma rede local, identificando as máquinas ativas de acordo com as respostas."
categories: "common"
---
> Mais informações: <https://github.com/royhills/arp-scan>.

- Verificar as máquinas da rede local:

```bash
arp-scan --localnet
```

- Verificar as máquinas de uma rede IP especificando a máscara de bit:

```bash
arp-scan 192.168.1.1/24
```

- Verificar as máquinas de uma rede IP que estejam em uma faixa de valores:

```bash
arp-scan 127.0.0.0-127.0.0.31
```

- Verificar as máquinas de uma rede IP especificando a máscara de rede:

```bash
arp-scan 10.0.0.0:255.255.255.0
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[gkah](mailto:47049232+Fivro@users.noreply.github.com) | arp-scan: move to common platform (#6395) | 2021-09-08T14:32:06 | [ef69c60c84c8](https://github.com/tldr-pages/tldr/commit/ef69c60c84c83ade68917e65c83476ab6c01ac9d)


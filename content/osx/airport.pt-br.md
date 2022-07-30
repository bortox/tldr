---
author: ['Andreia Bohner']
date: 1658135504
title: "airport"
description: "airport, Utilitário de configuração de rede sem fio."
categories: "osx"
---
> Mais informações: <https://ss64.com/osx/airport.html>.

- Mostrar informações de status da rede sem fio atual:

```bash
airport --getinfo
```

- Farejar tráfego de rede sem fio no canal 1:

```bash
airport sniff 1
```

- Procurar redes sem fio disponíveis:

```bash
airport --scan
```

- Desassociar da rede airport atual:

```bash
sudo airport --disassociate
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Andreia Bohner](mailto:andreiabohner@gmail.com) | airport: add pt_BR translation | 2022-07-18T11:11:44 | [171f16ffe413](https://github.com/tldr-pages/tldr/commit/171f16ffe413a44f29ac4ac81f7f705d3457c1df)


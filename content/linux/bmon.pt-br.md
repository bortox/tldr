---
author: ['Stig124', 'Marco Bonelli']
date: 1625841955
title: "bmon"
description: "bmon, Monitora a largura de banda e produz estatísticas relacionadas a rede."
categories: "linux"
---
> Mais informações: <https://github.com/tgraf/bmon>.

- Exibir uma lista com todas as interfaces de rede:

```bash
bmon -a
```

- Exibir as taxas de transferência de dados em bits por segundo:

```bash
bmon -b
```

- Definir quais interfaces serão visíveis:

```bash
bmon -p interface_1,interface_2,interface_3
```

- Definir o intervalo (em segundos) que a taxa por contador será calculada:

```bash
bmon -R 2.0
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)


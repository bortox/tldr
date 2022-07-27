---
author: ['Marco Bonelli', 'Stig124']
date: 1625841955
title: "dmesg, TLDR Pages"
description: "dmesg, Escreve as mensagens do kernel na terminal."
categories: "linux"
---
> Mais informações: <https://manned.org/dmesg>.

- Exibir as mensagens do kernel:

```bash
dmesg
```

- Exibir as mensagens de erro do kernel:

```bash
dmesg --level err
```

- Exibir as mensagens do kernel e manter o terminal esperando por novas menagens, semelhante ao `tail -f` (disponível nas versões 3.5.0 e superiores do kernel):

```bash
dmesg -w
```

- Exibir a quantidade de memória física disponível no sistema:

```bash
dmesg | grep -i memory
```

- Exibir as mensagens do kernel divididas em páginas:

```bash
dmesg | less
```

- Exibir as menagens do kernel com data/hora (disponível nas versões 3.5.0 e superiores do kernel):

```bash
dmesg -T
```

- Exibir as mensagens do kernel em um formato de fácil leitura (disponível nas versões 3.5.0 e superiores do kernel):

```bash
dmesg -H
```

- Exibir as mensagens do kernel utilizando cores (disponível nas versões 3.5.0 e superiores do kernel):

```bash
dmesg -L
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)


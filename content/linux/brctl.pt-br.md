---
author: ['Marco Bonelli', 'Stig124']
date: 1625841955
title: "brctl, TLDR Pages"
description: "brctl, Administração de pontes de rede."
categories: "linux"
---
> Mais informações: <https://manned.org/brctl>.

- Exibir uma lista com informações das pontes de rede existentes:

```bash
sudo brctl show
```

- Cria uma ponte de rede:

```bash
sudo brctl add nome_da_ponte
```

- Remover uma ponte de rede:

```bash
sudo brctl del nome_da_ponte
```

- Adicionar uma interface de rede em uma ponte de rede existente:

```bash
sudo brctl addif nome_da_ponte nome_da_interface_de_rede
```

- Remover uma interface de rede de uma ponte de rede existente:

```bash
sudo brctl delif nome_da_ponte nome_da_interface_de_rede
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)


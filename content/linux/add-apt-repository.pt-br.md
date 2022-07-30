---
author: ['Stig124', 'Marco Bonelli']
date: 1625841955
title: "add-apt-repository"
description: "add-apt-repository, Gerenciar definições de repositórios APT."
categories: "linux"
---
> Mais informações: <https://manned.org/apt-add-repository>.

- Adicionar um repositório:

```bash
add-apt-repository especificacao_do_repositorio
```

- Remover um repositório:

```bash
add-apt-repository --remove especificacao_do_repositorio
```

- Adicionar um repositório e atualizar o cache do(s) pacote(s) deste repositório:

```bash
add-apt-repository --update especificacao_do_repositorio
```

- Adicionar um repositório e habilitar o download do código fonte do(s) pacote(s) deste repositório:

```bash
add-apt-repository --enable-source especificacao_do_repositorio
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)


---
author: ['marchersimon', 'Simao Ferreira']
date: 1660133637
title: "pacman"
description: "pacman, Utilitário para gerir pacotes Arch Linux."
categories: "linux"
---
> Sub comandos como `pacman sync` tem a sua própria documentação.

> Mais informações: <https://man.archlinux.org/man/pacman.8>.

- Sincronizar e actualizar todos os pacotes:

```bash
sudo pacman -Syu
```

- Instalar um novo pacote:

```bash
sudo pacman -S package_name
```

- Remover um pacote e todas as dependencias:

```bash
sudo pacman -Rs nome_do_pacote
```

- Procurar um pacote na base de dados por palavra chave ou expressão regular (regex):

```bash
pacman -Ss "search_pattern"
```

- Listar versão dos pactotes instalados:

```bash
pacman -Q
```

- Listar versão dos pactotes instalados explicitamente:

```bash
pacman -Qe
```

- Listar pacotes órfãos (instalados como dependencia mas não exigidos por nenhum pacote):

```bash
pacman -Qtdq
```

- Remover memória armazenada (cache) do `pacman`:

```bash
sudo pacman -Scc
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pacman: use short options only (#8286) | 2022-08-10T14:13:57 | [1f147d6b91a6](https://github.com/tldr-pages/tldr/commit/1f147d6b91a67044e5f60817a0355d2acd40bb88)
[Simao Ferreira](mailto:24299428+simao-ferreira@users.noreply.github.com) | pacman: add pt_PT translation (#7630) | 2022-01-12T14:21:03 | [9e94d88d31d7](https://github.com/tldr-pages/tldr/commit/9e94d88d31d7c609fa13f15284094e21c93e0132)


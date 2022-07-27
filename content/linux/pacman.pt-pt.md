---
author: ['Simao Ferreira']
date: 1641993663
title: "pacman, TLDR Pages"
description: "pacman, Utilitário para gerir pacotes Arch Linux."
categories: "linux"
---
> Sub comandos como `pacman sync` tem a sua própria documentação.

> Mais informações: <https://man.archlinux.org/man/pacman.8>.

- Sincronizar e actualizar todos os pacotes:

```bash
sudo pacman --sync --refresh --sysupgrade
```

- Instalar um novo pacote:

```bash
sudo pacman --sync package_name
```

- Remover um pacote e todas as dependencias:

```bash
sudo pacman --remove --recursive nome_do_pacote
```

- Procurar um pacote na base de dados por palavra chave ou expressão regular (regex):

```bash
pacman --sync --search "search_pattern"
```

- Listar versão dos pactotes instalados:

```bash
pacman --query
```

- Listar versão dos pactotes instalados explicitamente:

```bash
pacman --query --explicit
```

- Listar pacotes órfãos (instalados como dependencia mas não exigidos por nenhum pacote):

```bash
pacman --query --unrequired --deps --quiet
```

- Remover memória armazenada (cache) do `pacman`:

```bash
sudo pacman --sync --clean --clean
```
Lista de alterações feitas a esta documentação


Autor | Descrição | Formato de data ISO 8601 | Ligação a GitHub
------|-----|-----|-----
[Simao Ferreira](mailto:24299428+simao-ferreira@users.noreply.github.com) | pacman: add pt_PT translation (#7630) | 2022-01-12T14:21:03 | [9e94d88d31d7](https://github.com/tldr-pages/tldr/commit/9e94d88d31d7c609fa13f15284094e21c93e0132)


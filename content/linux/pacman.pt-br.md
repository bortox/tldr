---
author: ['marchersimon', 'Ricardo H H Kojo', 'lincc']
date: 1660133637
title: "pacman"
description: "pacman, Utilitário de Arch Linux para gerenciamento de pacotes."
categories: "linux"
---
> Alguns subcomandos como `pacman sync` possuem sua própria documentação de uso.

> Mais informações: <https://man.archlinux.org/man/pacman.8>.

- Sincroniza e atualiza todos os pacotes:

```bash
sudo pacman -Syu
```

- Instala um novo pacote:

```bash
sudo pacman -S nome_do_pacote
```

- Remove um pacote e suas dependências:

```bash
sudo pacman -Rs nome_do_pacote
```

- Procura no banco de dados de pacotes por uma expressão regular ou palavra-chave:

```bash
pacman -Ss "padrao_buscado"
```

- Lista pacotes instalados e versões:

```bash
pacman -Q
```

- Lista apenas os pacotes explicitamente instalados e versões:

```bash
pacman -Qe
```

- Lista pacotes órfãos (instalado como dependência mas não requerido por qualquer pacote):

```bash
pacman -Qtdq
```

- Esvazia completamente o cache do pacman:

```bash
sudo pacman -Scc
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pacman: use short options only (#8286) | 2022-08-10T14:13:57 | [1f147d6b91a6](https://github.com/tldr-pages/tldr/commit/1f147d6b91a67044e5f60817a0355d2acd40bb88)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pacman: add sudo and use long options (#7132) | 2021-10-25T04:10:33 | [c9b534415099](https://github.com/tldr-pages/tldr/commit/c9b534415099cd2931eaf120938f201240c521a8)
[Ricardo H H Kojo](mailto:ricardo.kojo.dev@gmail.com) | pacman: add pt_BR translation Signed-off-by: Ricardo H H Kojo <ricardo.kojo.dev@gmail.com> | 2021-10-13T14:01:46 | [6350b3680086](https://github.com/tldr-pages/tldr/commit/6350b3680086f700d98f9e3c4cbcd3569c45e90d)


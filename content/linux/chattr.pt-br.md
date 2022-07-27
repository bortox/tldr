---
author: ['Marco Bonelli', 'Stig124']
date: 1625841955
title: "chattr, TLDR Pages"
description: "chattr, Altera os atributos de arquivos ou diretórios."
categories: "linux"
---
> Mais informações: <https://manned.org/chattr>.

- Bloquear um arquivo ou diretório para mudanças ou remoção, mesmo para um super usuário:

```bash
chattr +i caminho_do_arquivo_ou_diretorio
```

- Desbloquear um arquivo ou diretório:

```bash
chattr -i caminho_do_arquivo_ou_diretorio
```

- Bloquear diretório e todos os seus arquivos para mudanças ou remoção:

```bash
chattr -R +i caminho_do_diretorio
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)


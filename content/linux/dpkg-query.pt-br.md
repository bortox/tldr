---
author: ['Marco Bonelli', 'Stig124']
date: 1625841955
title: "dpkg-query, TLDR Pages"
description: "dpkg-query, Ferramenta que mostra informações dos pacotes instalados."
categories: "linux"
---
> Mais informações: <https://manpages.debian.org/latest/dpkg/dpkg-query.1.html>.

- Exibir os pacotes instalados:

```bash
dpkg-query -l
```

- Exibir os pacotes instalados correspondentes ao critério de busca:

```bash
dpkg-query -l 'criterio_de_busca'
```

- Exibir todos os arquivos instalados por um pacote:

```bash
dpkg-query -L nome_do_pacote
```

- Exibir informações sobre um pacote:

```bash
dpkg-query -s nome_do_pacote
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)


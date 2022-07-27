---
author: ['Marco Bonelli', 'Stig124', 'Guido Lena Cota']
date: 1625841955
title: "apk, TLDR Pages"
description: "apk, Gerenciador de pacotes da distribuição Alpine."
categories: "linux"
---
> Mais informações: <https://wiki.alpinelinux.org/wiki/Alpine_Linux_package_management>.

- Atualizar os índices dos pacotes disponíveis:

```bash
apk update
```

- Instalar um pacote:

```bash
apk add pacote
```

- Remover um pacote:

```bash
apk del pacote
```

- Reparar ou atualizar um pacote sem modificar as principais dependências:

```bash
apk fix pacote
```

- Procurar um pacote especificando alguma palavra-chave:

```bash
apk search palavra_chave
```

- Exibir informações sobre um pacote:

```bash
apk info pacote
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | multiple pages: Use snake_case in token syntax (#4788) | 2020-11-01T14:40:05 | [0bb9c353a717](https://github.com/tldr-pages/tldr/commit/0bb9c353a717513283f8cda8493e5370ca47219a)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)


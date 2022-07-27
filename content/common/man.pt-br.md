---
author: ['Patrice Denis', 'Marco Bonelli', 'Noy', 'Rui Alves', 'Guido Lena Cota']
date: 1631536931
title: "man, TLDR Pages"
description: "man, Utilitário para exibir páginas do manual."
categories: "common"
---
> Mais informações: <https://www.man7.org/linux/man-pages/man1/man.1.html>.

- Visualizar o manual de um comando:

```bash
man comando
```

- Visualizar a página da seção 7 do manual de um comando:

```bash
man 7 comando
```

- Visualizar o caminho procurado pelas páginas do manual:

```bash
man --path
```

- Visualizar o caminho do manual de um comando:

```bash
man -w comando
```

- Procurar manuais contendo um termo de pesquisa:

```bash
man -k "termo_de_pesquisa"
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Noy](mailto:nbaltunian@gmail.com) | man: correct syntax (#6505) | 2021-09-13T14:42:11 | [efeee14594da](https://github.com/tldr-pages/tldr/commit/efeee14594dab9cc5dd082f03a53dbfa83298fb0)
[Patrice Denis](mailto:patrice.denis@gmail.com) | man: add more info link and --locale example (#5504) | 2021-03-25T22:54:01 | [b431ae33f75d](https://github.com/tldr-pages/tldr/commit/b431ae33f75dbfc3d554f9e611b4f1301ce12885)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | multiple pages: Use snake_case in token syntax (#4788) | 2020-11-01T14:40:05 | [0bb9c353a717](https://github.com/tldr-pages/tldr/commit/0bb9c353a717513283f8cda8493e5370ca47219a)
[Marco Bonelli](mailto:marco@mebeim.net) | bat, bg, cmus, man (pt_BR): fix broken description. | 2019-10-25T14:27:07 | [4484fd55c2ab](https://github.com/tldr-pages/tldr/commit/4484fd55c2aba7fec86030afe5429545c82b7f8c)
[Rui Alves](mailto:up201606746@fe.up.pt) | man: add pt_BR translation (#3405) | 2019-10-17T17:58:30 | [eacd938fcafb](https://github.com/tldr-pages/tldr/commit/eacd938fcafbee3010faa05afed789e9a91730d7)


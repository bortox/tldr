---
author: ['Marco Bonelli', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1633112881
title: "ack"
description: "ack, Uma ferramenta de pesquisa similar ao grep, otimizada para programadores."
categories: "common"
---
> Mais informações: <https://beyondgrep.com/documentation>.

- Procurar por arquivos que contenham o termo "foo":

```bash
ack foo
```

- Procurar por arquivos em uma linguagem específica:

```bash
ack --ruby each_with_object
```

- Contar o número total de correspondências para o termo "foo":

```bash
ack -ch foo
```

- Mostrar o nome dos arquivos contendo o termo "foo" e o número de correspondências em cada arquivo:

```bash
ack -cl foo
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages (pt_BR): fix homepage tokens (#3340) | 2019-10-07T15:31:50 | [83b623d988f7](https://github.com/tldr-pages/tldr/commit/83b623d988f7940581b5e9fbd43ec0fdc7496a68)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)


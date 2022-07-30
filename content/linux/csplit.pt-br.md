---
author: ['Dario Vladović', 'Marco Bonelli', 'marchersimon']
date: 1620637392
title: "csplit"
description: "csplit, Divide um arquivo em várias partes."
categories: "linux"
---
> O padrão de nomenclatura dos arquivos será "xx00", "xx01" e assim por diante.

> Mais informações: <https://www.gnu.org/software/coreutils/csplit>.

- Dividir um arquivo nas linhas 5 e 23:

```bash
csplit arquivo 5 23
```

- Dividir um arquivo a cada 5 linhas (este comando irá falhar se o total de linhas do arquivo não for divisível por 5):

```bash
csplit arquivo 5 {*}
```

- Dividir um arquivo a cada 5 linhas, ignorando o fato do total de linhas ser divisível por 5:

```bash
csplit -k arquivo 5 {*}
```

- Dividir o arquivo na linha 5 e utilizar um prefixo específico para os arquivos de saída:

```bash
csplit arquivo 5 -f prefix
```

- Dividir um arquivo na linha que atenda a expressão regular:

```bash
csplit arquivo /expressao_regular/
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | csplit: add more information link (#5575) | 2021-03-30T12:10:07 | [5d92e443194d](https://github.com/tldr-pages/tldr/commit/5d92e443194da437deea00618a8bd37511ba99f5)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)


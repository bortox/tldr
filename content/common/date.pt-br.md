---
author: ['Thiago Daniel Cagnoni de Pauli']
date: 1635359830
title: "date"
description: "date, Define ou exibe a data e horário do sistema."
categories: "common"
---
> Mais informações: <https://www.gnu.org/software/coreutils/date>.

- Exibe a data atual usando a formatação padrão:

```bash
date +"%c"
```

- Exibe a data atual no formato UTC e ISO 8601:

```bash
date -u +"%Y-%m-%dT%H:%M:%SZ"
```

- Mostra a data atual em Unix timestamp - segundos desde 00:00:00 UTC de 1 de janeiro de 1970 (Unix epoch):

```bash
date +%s
```

- Exibe uma data representada como Unix timestamp utilizando a formatação padrão:

```bash
date -d @1473305798
```

- Converte uma data específica pra Unix timestamp:

```bash
date -d "2018-09-01 00:00" +%s --utc
```

- Exibe a data atual no formato RFC-3339 (`YYYY-MM-DD hh:mm:ss TZ`):

```bash
date --rfc-3339=s
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Thiago Daniel Cagnoni de Pauli](mailto:39651883+Float07@users.noreply.github.com) | date, diff, pip, pip3: add pt_BR translation (#7176) | 2021-10-27T20:37:10 | [c5c7a9ec9e81](https://github.com/tldr-pages/tldr/commit/c5c7a9ec9e81a904857cadad3a9c4de53035356c)


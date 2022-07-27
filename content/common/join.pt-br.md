---
author: ['Gabriel Rodrigues']
date: 1633877353
title: "join, TLDR Pages"
description: "join, Junta linhas de dois arquivos ordenados em um campo comum."
categories: "common"
---
> Mais informações: <https://www.gnu.org/software/coreutils/join>.

- Junta dois arquivos no primeiro campo (padrão):

```bash
join arquivo1 arquivo2
```

- Junta dois arquivos usando uma vírgula (em vez de um espaço) como separador de campo:

```bash
join -t ',' arquivo1 arquivo2
```

- Junta campo3 do arquivo1 ao campo1 do arquivo2:

```bash
join -1 3 -2 1 arquivo1 arquivo2
```

- Produz uma linha para cada linha que não pode ser pareada para o arquivo1:

```bash
join -a 1 arquivo1 arquivo2
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Gabriel Rodrigues](mailto:gabrxzvski@gmail.com) | join: add pt_BR translation | 2021-10-10T16:49:13 | [39fac93c4db4](https://github.com/tldr-pages/tldr/commit/39fac93c4db44a5377cc57853cf6b47b1dc191b0)


---
author: ['Dario Vladović', 'Nolasco Napoleão', 'marchersimon']
date: 1617292466
title: "touch, TLDR Pages"
description: "touch, Atualizar as timestamps de um arquivo para a hora atual."
categories: "common"
---
> Se o arquivo não existir, cria um arquivo vazio, a menos que seja passado o parâmetro -c ou -h.

> Mais informações: <https://www.gnu.org/software/coreutils/touch>.

- Criar um novo arquivo vazio, ou atualizar as timestamps para a hora atual:

```bash
touch arquivo
```

- Definir as timestamps de um arquivo para a hora especificada:

```bash
touch -t YYYYMMDDHHMM.SS arquivo
```

- Usar as timestamps do arquivo1 para definir as timestamps do arquivo2:

```bash
touch -r arquivo1 arquivo2
```

- Alterar as timestamps de um arquivo. Não cria novo arquivo se não existir:

```bash
touch -c arquivo
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | touch: change link (#5550) | 2021-03-30T09:15:08 | [64814bb7bac0](https://github.com/tldr-pages/tldr/commit/64814bb7bac00f937c245a550a19dc2c4b62d14f)
[Nolasco Napoleão](mailto:nolascoamadonapoleao@gmail.com) | touch: add Portuguese translation (#3485) Co-authored-by: Waldir Pimenta <waldyrious@gmail.com> | 2019-12-24T15:02:36 | [cfc49559e8da](https://github.com/tldr-pages/tldr/commit/cfc49559e8da6194c2ebe62993621ff2168d30a5)


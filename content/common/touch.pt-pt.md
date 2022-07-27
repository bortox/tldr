---
author: ['Waldir Pimenta', 'Dario Vladović', 'Nolasco Napoleão', 'marchersimon']
date: 1617292466
title: "touch, TLDR Pages"
description: "touch, Atualizar as timestamps de um ficheiro para a hora atual."
categories: "common"
---
> Se o ficheiro não existir, cria um ficheiro vazio, a menos que seja passado o parâmetro -c ou -h.

> Mais informações: <https://www.gnu.org/software/coreutils/touch>.

- Criar um novo ficheiro vazio, ou atualizar as timestamps para a hora atual:

```bash
touch ficheiro
```

- Definir as timestamps de um ficheiro para a hora especificada:

```bash
touch -t YYYYMMDDHHMM.SS ficheiro
```

- Usar as timestamps do ficheiro1 para definir as timestamps do ficheiro2:

```bash
touch -r ficheiro1 ficheiro2
```

- Alterar as timestamps de um ficheiro. Não cria novo ficheiro se não existir:

```bash
touch -c ficheiro
```
Lista de alterações feitas a esta documentação


Autor | Descrição | Formato de data ISO 8601 | Ligação a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | touch: change link (#5550) | 2021-03-30T09:15:08 | [64814bb7bac0](https://github.com/tldr-pages/tldr/commit/64814bb7bac00f937c245a550a19dc2c4b62d14f)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | multiple pages: use infinitive in command descriptions of pt-PT pages (#4235) | 2020-07-31T15:27:03 | [94ca63897660](https://github.com/tldr-pages/tldr/commit/94ca638976601493bbaa51837b3d0bda4561fa87)
[Nolasco Napoleão](mailto:nolascoamadonapoleao@gmail.com) | Apply suggestions from code review Co-Authored-By: Waldir Pimenta <waldyrious@gmail.com> | 2020-04-03T22:41:52 | [b9d7ca6ff1b1](https://github.com/tldr-pages/tldr/commit/b9d7ca6ff1b1923a94f989872a7600282b62e3a1)
[Nolasco Napoleão](mailto:nolascoamadonapoleao@gmail.com) | touch: add Portuguese translation | 2020-04-03T22:41:52 | [f5343b981f44](https://github.com/tldr-pages/tldr/commit/f5343b981f44fc8b9edbf928c4aba936389b7124)


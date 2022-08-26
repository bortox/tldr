---
author: ['Nolasco Napoleão', 'marchersimon', 'Dario Vladović', 'Luis Saes']
date: 1661428811
title: "touch"
description: "touch, Alterar os timestamps de acesso e de modificação (atime, mtime) de um arquivo."
categories: "common"
---
> Mais informações: <https://www.gnu.org/software/coreutils/touch>.

- Criar novo(s) arquivo(s) vazio(s) ou alterar os timestamps do(s) arquivo(s) para o timestamp atual:

```bash
touch caminho/para/arquivo
```

- Definir os timestamps de um arquivo para uma data e hora específica:

```bash
touch -t YYYYMMDDHHMM.SS caminho/para/arquivo
```

- Definir os timestamps de um arquivo para uma hora no passado:

```bash
touch -d "-1 hour" caminho/para/arquivo
```

- Usar as timestamps de um arquivo para definir as timestamps de um segundo arquivo:

```bash
touch -r caminho/para/arquivo1 caminho/para/arquivo2
```

- Criar múltiplos arquivos:

```bash
touch -c caminho/para/arquivo{1,2,3}.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Luis Saes](mailto:55040458+luis-saes@users.noreply.github.com) | pip, pip-install, pip-uninstall, touch: add pt_BR translation (#8396) * touch: update pt_BR translation * pip: update pt_BR [...] | 2022-08-25T14:00:11 | [e2d938796595](https://github.com/tldr-pages/tldr/commit/e2d938796595c72fcf1cd92896b9bba07a58eb7a)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | touch: change link (#5550) | 2021-03-30T09:15:08 | [64814bb7bac0](https://github.com/tldr-pages/tldr/commit/64814bb7bac00f937c245a550a19dc2c4b62d14f)
[Nolasco Napoleão](mailto:nolascoamadonapoleao@gmail.com) | touch: add Portuguese translation (#3485) Co-authored-by: Waldir Pimenta <waldyrious@gmail.com> | 2019-12-24T15:02:36 | [cfc49559e8da](https://github.com/tldr-pages/tldr/commit/cfc49559e8da6194c2ebe62993621ff2168d30a5)


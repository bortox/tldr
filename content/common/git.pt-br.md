---
author: ['André Almeida', 'Axel Navarro', 'Gustavo Cavalieri Fernandes', 'bl-ue', 'marchersimon']
date: 1633457023
title: "git"
description: "git, Sistema de versionamento distribuído."
categories: "common"
---
> Alguns subcomandos como `git commit` tem sua própia documentação de uso.

> Mais informações: <https://git-scm.com/>.

- Verifique a versão do Git:

```bash
git --version
```

- Mostre ajuda geral:

```bash
git --help
```

- Mostre ajuda de um subcomando do Git (como `commit`, `log`, etc.):

```bash
git help subcomando
```

- Execute um subcomando Git:

```bash
git subcomando
```

- Execute um subcomando Git no caminho raíz de um repositório específico:

```bash
git -C caminho/para/repo subcomando
```

- Execute um subcomando Git com uma dada configuração:

```bash
git -c 'config.chave=valor' subcomando
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gustavo Cavalieri Fernandes](mailto:gugacavalieri@gmail.com) | *: mention subcommands in pt_BR translation (#6798) | 2021-10-05T20:03:43 | [ed5274772bd2](https://github.com/tldr-pages/tldr/commit/ed5274772bd2b09eb465abfd4e132f47048783a2)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Axel Navarro](mailto:navarroaxel@gmail.com) | git: normalize caminho para repo | 2021-05-08T21:25:38 | [afec953b26bd](https://github.com/tldr-pages/tldr/commit/afec953b26bd75780fcde5be8166c7e7e3964799)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Portuguese (Brazil) pages: fix (valid) tldr-lint errors (#5369) | 2021-03-08T20:42:47 | [443568f165ec](https://github.com/tldr-pages/tldr/commit/443568f165eccbfa2521da66158f07e4e9d3bd7a)
[André Almeida](mailto:andrealmeid@riseup.net) | git*: add pt_BR translation (#4688) | 2020-10-15T14:19:51 | [6264983e6980](https://github.com/tldr-pages/tldr/commit/6264983e69803c46fd45d86ecea6c79ea5f61104)


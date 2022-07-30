---
author: ['FilipaDurao', 'bl-ue']
date: 1617130649
title: "alias"
description: "alias, Cria um alias -- palavras que são substituídas por um comando."
categories: "common"
---
> Alias expiram com a sessão da shell atual, a menos que sejam definidos no ficheiro de configuração da shell, por exemplo `~/.bashrc`.

> Mais informações: <https://tldp.org/LDP/abs/html/aliases.html>.

- Listar todos os alias:

```bash
alias
```

- Criar um alias genérico:

```bash
alias palavra="comando"
```

- Visualizar o comando associado a um dado alias:

```bash
alias palavra
```

- Remover um alias de um comando:

```bash
unalias palavra
```

- Tornar `rm` num comando interativo:

```bash
alias rm="rm -i"
```

- Criar `la` como um atalho para `ls -a`:

```bash
alias la="ls -a"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | alias: add more information link (#5644) | 2021-03-30T20:57:29 | [edd9c5a5dc32](https://github.com/tldr-pages/tldr/commit/edd9c5a5dc32839ecf45b50d02d0260b8032002e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[FilipaDurao](mailto:32716065+FilipaDurao@users.noreply.github.com) | alias: add Portuguese translation (#4416) | 2020-10-05T16:11:59 | [37fe585626a1](https://github.com/tldr-pages/tldr/commit/37fe585626a1fa9df07fa07a94254514127d3b86)


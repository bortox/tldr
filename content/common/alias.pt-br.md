---
author: ['bl-ue', 'Marco Bonelli']
date: 1617130649
title: "alias"
description: "alias, Cria apelidos -- palavras que são substituídas por um comando."
categories: "common"
---
> Apelidos expiram ao final da sessão atual do shell de comando, a menos que sejam definidos no arquivo de configuração do shell, por exemplo `~/.bashrc`.

> Mais informações: <https://tldp.org/LDP/abs/html/aliases.html>.

- Criar um apelido:

```bash
alias apelido="comando"
```

- Visualizar o comando associado a um determinado apelido:

```bash
alias apelido
```

- Remover um apelido:

```bash
unalias apelido
```

- Exibir todos os apelidos definidos:

```bash
alias -p
```

- Tornar o comando `rm` interativo:

```bash
alias rm="rm -i"
```

- Criar o apelido `la` como um atalho para `ls -a`:

```bash
alias la="ls -a"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | alias: add more information link (#5644) | 2021-03-30T20:57:29 | [edd9c5a5dc32](https://github.com/tldr-pages/tldr/commit/edd9c5a5dc32839ecf45b50d02d0260b8032002e)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)


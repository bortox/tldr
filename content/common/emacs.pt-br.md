---
author: ['André Viana']
date: 1635796617
title: "emacs"
description: "emacs, O editor extensível, personalizável, autodocumentável, com exibição em tempo real."
categories: "common"
---
> Veja também `emacsclient`.

> Mais informações: <https://www.gnu.org/software/emacs>.

- Inicia o Emacs e abra um arquivo:

```bash
emacs caminho/para/arquivo
```

- Abre um arquivo em uma linha especificada:

```bash
emacs +numero_linha caminho/para/arquivo
```

- Inicia o Emacs em modo console (sem uma janela X):

```bash
emacs --no-window-system
```

- Inicia um servidor Emacs em segundo plano (acessível através do `emacsclient`):

```bash
emacs --daemon
```

- Para um servidor Emacs em funcionamento e todas as suas instâncias, pedindo confirmação em arquivos não salvos:

```bash
emacsclient --eval '(save-buffers-kill-emacs)'
```

- Salva um arquivo em Emacs:

```bash
Ctrl + X, Ctrl + S
```

- Deixa o Emacs:

```bash
Ctrl + X, Ctrl + C
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[André Viana](mailto:andrebermudesviana@gmail.com) | emacs: add pt_BR translation (#7297) | 2021-11-01T20:56:57 | [f68899afa604](https://github.com/tldr-pages/tldr/commit/f68899afa60485d8de51ea716cda708e14ec47e0)


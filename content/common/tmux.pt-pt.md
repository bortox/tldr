---
author: ['Gonçalo Silva']
date: 1601850166
title: "tmux, TLDR Pages"
description: "tmux, Multiplexador do terminal. Permite várias sessões com janelas, painéis e muito mais."
categories: "common"
---
> Mais informações: <https://github.com/tmux/tmux>.

- Iniciar uma nova sessão:

```bash
tmux
```

- Iniciar uma sessão com nome:

```bash
tmux new-session -s nome
```

- Listar sessões existentes:

```bash
tmux ls
```

- Entrar na última sessão utilizada:

```bash
tmux attach-session
```

- Entrar numa sessão com nome:

```bash
tmux attach-session -t nome
```

- Sair da sessão atual (com o prefixo Ctrl-B):

```bash
Ctrl-B d
```

- Eliminar uma sessão com nome:

```bash
tmux kill-session -t nome
```

- Eliminar a sessão atual (com o prefixo Ctrl-B):

```bash
Ctrl-B :kill-session<Enter>
```
Lista de alterações feitas a esta documentação


Autor | Descrição | Formato de data ISO 8601 | Ligação a GitHub
------|-----|-----|-----
[Gonçalo Silva](mailto:27678178+gplgps@users.noreply.github.com) | tmux: add pt_PT translation (#4458) | 2020-10-05T00:22:46 | [af1ed4fd21d7](https://github.com/tldr-pages/tldr/commit/af1ed4fd21d7e0be18748c739b73d9034b67ebb2)


---
author: ['jvktr']
date: 1593982449
title: "i3lock, TLDR Pages"
description: "i3lock, Bloqueador de tela simples para o i3wm."
categories: "linux"
---
> Mais informações: <https://i3wm.org/i3lock>.

- Bloqueia a tela com uma cor de fundo (formato rrggbb):

```bash
i3lock -c 0000ff
```

- Bloqueia a tela com uma imagem PNG:

```bash
i3lock -i local/da/imagem.png
```

- Desabilita o indicador de desbloqueio (remove a resposta ao apertar teclas):

```bash
i3lock -u
```

- Exibe o ponteiro do mouse ao invés de ocultá-lo ('default' para o ponteiro padrão, 'win' para um ponteiro MS Windows):

```bash
i3lock -p default|win
```

- Bloqueia a tela com uma imagem PNG exibida em múltiplos monitores, com o ponteiro do mouse habilitado:

```bash
i3lock -i local/da/imagem.png -p default|win -t
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[jvktr](mailto:67814222+jvktr@users.noreply.github.com) | i3lock: add page (EN/pt_BR) (#4146) | 2020-07-05T22:54:09 | [07d98683896d](https://github.com/tldr-pages/tldr/commit/07d98683896deca8ca65c49ac7dd3cb506302c02)


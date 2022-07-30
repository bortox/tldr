---
author: ['Iván Hernández Cazorla']
date: 1579229976
title: "tmux"
description: "tmux, Multiplexa varias consolas virtuales."
categories: "common"
---
> Más información: <https://github.com/tmux/tmux>.

- Inicia una nueva sesión de tmux:

```bash
tmux
```

- Inicia una nueva sesión de tmux y le asigna un nombre:

```bash
tmux new -s nombre
```

- Muestra las sesiones:

```bash
tmux ls
```

- Adjunta a una sesión:

```bash
tmux a
```

- Adjunta a una sesión con un nombre específico:

```bash
tmux a -t nombre
```

- Desconecta de la sesión:

```bash
Ctrl + B, D
```

- Elimina una sesión con un nombre específico:

```bash
tmux kill-session -t nombre
```

- Elimina una sesión cuando se adjunta:

```bash
Ctrl + B, x (luego se pulsa 'y' para confirmar que sí)
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Iván Hernández Cazorla](mailto:ivan@ivanhercaz.com) | tmux: add Spanish translation (#3762) | 2020-01-17T03:59:36 | [711a1c4afb59](https://github.com/tldr-pages/tldr/commit/711a1c4afb5913d0bdcaf489210e4290cd369a9e)


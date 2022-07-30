---
author: ['derNiklaas', 'Gustavo Cavalieri Fernandes']
date: 1633404950
title: "watch"
description: "watch, Executa um comando repetidas vezes, e monitora a saída em tela cheia."
categories: "linux"
---
> Mais informações: <https://manned.org/watch>.

- Monitora arquivos no diretório atual:

```bash
watch ls
```

- Monitora espaço em disco e destaca as alterações:

```bash
watch -d df
```

- Monitora processos "node", atualizando a cada 3 segundos:

```bash
watch -n 3 "ps aux | grep node"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[derNiklaas](mailto:derNiklaas@users.noreply.github.com) | wall, watch, whereis, whiptail, wipefs, wmctrl, wodim: add link (#6784) | 2021-10-05T05:35:50 | [e0442c6f98f5](https://github.com/tldr-pages/tldr/commit/e0442c6f98f5e01ffc3acd1398249cf0a8a3673d)
[Gustavo Cavalieri Fernandes](mailto:gugacavalieri@gmail.com) | watch: add pt_BR translation (#6014) | 2021-05-24T14:06:01 | [2cf4c9aa667a](https://github.com/tldr-pages/tldr/commit/2cf4c9aa667a7a56abe2171d08740d5894e06f64)


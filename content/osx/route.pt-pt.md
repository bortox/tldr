---
author: ['Rúben Silva', 'git-em']
date: 1646140877
title: "route"
description: "route, Alteração manual da tabela de rotas."
categories: "osx"
---
> Necessita de root.

> Mais informações: <https://www.manpagez.com/man/8/route/>.

- Adiciona uma rota para um destino passando por um gateway:

```bash
sudo route add endereco_ip_destino endereco_gateway
```

- Adiciona uma rota para um rede /24 passando por um gateway:

```bash
sudo route add endereco_ip_subnet/24 endereco_gateway
```

- Corre em modo de teste (não realiza alterações, apenas a mostra):

```bash
sudo route -t add endereco_ip_destino/24 endereco_gateway
```

- Remove todas as rotas:

```bash
sudo route flush
```

- Remove uma rota especifica:

```bash
sudo route delete endereco_ip_destino/24
```

- Procura e mostra a rota para um destino (nome da máquina ou endereço IP):

```bash
sudo route get destino
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | brightness, n, open, pbcopy, pbpaste, rename, route, rubocop, softwareupdate, timed, where, while, xed, xip: add link (#7831) | 2022-03-01T14:21:17 | [2ce63b334ebd](https://github.com/tldr-pages/tldr/commit/2ce63b334ebd26bb9e46be904fcc19884974e397)
[Rúben Silva](mailto:rubensilva945@gmail.com) | rename, route: add pt_PT translation (#7067) | 2021-10-19T10:20:24 | [07dcece3a4d5](https://github.com/tldr-pages/tldr/commit/07dcece3a4d538d45c4c6dddad392072081c4769)


---
author: ['Gustavo Cavalieri Fernandes']
date: 1633451463
title: "flatpak"
description: "flatpak, Construa, instale e execute aplicações e plataformas flatpak."
categories: "linux"
---
> Mais informações: <https://docs.flatpak.org/en/latest/flatpak-command-reference.html#flatpak>.

- Executar uma aplicação instalada:

```bash
flatpak run nome
```

- Instalar uma aplicação de uma fonte remota:

```bash
flatpak install remoto nome
```

- Listar todas as aplicações e plataformas instaladas:

```bash
flatpak list
```

- Atualizar todas as aplicações e plataformas instaladas:

```bash
flatpak update
```

- Adicionar uma fonte remota:

```bash
flatpak remote-add --if-not-exists nome_remoto url_remoto
```

- Listar todas fontes remotas configuradas:

```bash
flatpak remote-list
```

- Remover uma aplicação instalada:

```bash
flatpak remove nome
```

- Mostrar informações sobre uma aplicação instalada:

```bash
flatpak info nome
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gustavo Cavalieri Fernandes](mailto:gugacavalieri@gmail.com) | flatpak: add pt_BR translation (#6751) | 2021-10-05T18:31:03 | [48d6a1efbd13](https://github.com/tldr-pages/tldr/commit/48d6a1efbd134f488aa62b7c39b0221a8d538c20)


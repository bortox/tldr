---
author: ['João C Fukuda']
date: 1634005207
title: "alacritty, TLDR Pages"
description: "alacritty, Terminal multiplataforma, acelerado por GPU."
categories: "common"
---
> Mais informações: <https://github.com/alacritty/alacritty>.

- Abre uma nova janela do Alacritty:

```bash
alacritty
```

- Roda em um diretório específico:

```bash
alacritty --working-directory caminho/para/diretório
```

- Roda um comando em uma nova janela do Alacritty:

```bash
alacritty -e comando
```

- Especifica um arquivo de configuração alternativo (`$XDG_CONFIG_HOME/alacritty/alacritty.yml` por padrão):

```bash
alacritty --config-file caminho/para/config.yml
```

- Executa com configuração ao vivo habilitada (pode também ser habilitada por padrão no `alacritty.yml`):

```bash
alacritty --live-config-reload --config-file caminho/para/config.yml
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[João C Fukuda](mailto:37672942+JoaoFukuda@users.noreply.github.com) | alacritty: add pt_BR translation (#6888) | 2021-10-12T04:20:07 | [d8604de17a71](https://github.com/tldr-pages/tldr/commit/d8604de17a71c5aacb34e50b0af4b0add03e288a)


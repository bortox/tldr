---
author: ['Simao Ferreira']
date: 1642278201
title: "alacritty"
description: "alacritty, Emulador de terminal multiplataforma acelerado por GPU."
categories: "common"
---
> Mais informações: <https://github.com/alacritty/alacritty>.

- Abrir Alacritty numa nova janela:

```bash
alacritty
```

- Executar na directoria especificada:

```bash
alacritty --working-directory caminho/para/directoria
```

- Executar commando numa nova janela de Alacritty:

```bash
alacritty -e comando
```

- Definir caminho alternativo para o ficheiro de configuração (por omissão `$XDG_CONFIG_HOME/alacritty/alacritty.yml`):

```bash
alacritty --config-file caminho/para/configuração.yml
```

- Executar com carregamento automático de configuração (pode ser definido por omissão em `alacritty.yml`):

```bash
alacritty --live-config-reload --config-file caminho/para/configuração.yml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Simao Ferreira](mailto:24299428+simao-ferreira@users.noreply.github.com) | alacritty: add pt_PT translation (#7656) | 2022-01-15T21:23:21 | [fef0e3a6b586](https://github.com/tldr-pages/tldr/commit/fef0e3a6b5863c6f385af0f14bcfb73d6adde6ad)


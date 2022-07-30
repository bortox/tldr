---
author: ['4n7hem']
date: 1635016121
title: "firefox"
description: "firefox, Um browser livre e de código aberto."
categories: "common"
---
> Mais informações: <https://developer.mozilla.org/en-US/docs/Mozilla/Command_Line_Options>.

- Inicie o Firefox e abra uma página web:

```bash
firefox https://www.duckduckgo.com
```

- Abra uma nova janela:

```bash
firefox --new-window https://www.duckduckgo.com
```

- Abra uma janela privativa (incognito):

```bash
firefox --private-window
```

- Pesquise por "wikipedia" usando a engine de busca padrão:

```bash
firefox --search "wikipedia"
```

- Inicie o Firefox no modo seguro, com todas as extensões desativadas:

```bash
firefox --safe-mode
```

- Tire uma screenshot de uma página web no modo headless:

```bash
firefox --headless --screenshot caminho/para/arquivo_de_saida.png https://exemplo.com/
```

- Use um perfil específico para permitir que múltiplas instâncias separadas do Firefox rodem ao mesmo tempo:

```bash
firefox --profile caminho/para/diretório https://example.com/
```

- Configure o Firefox como o navegador padrão:

```bash
firefox --setDefaultBrowser
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[4n7hem](mailto:48725919+4n7hem@users.noreply.github.com) | firefox: add pt_BR translation (#7144) | 2021-10-23T21:08:41 | [d8345037430f](https://github.com/tldr-pages/tldr/commit/d8345037430fbf73d9b3de468a31ad058ec03055)


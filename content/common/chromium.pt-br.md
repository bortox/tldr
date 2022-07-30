---
author: ['alexsantee', 'marchersimon']
date: 1659075216
title: "chromium, TLDR Pages"
description: "chromium, Navegador código aberto do Google."
categories: "common"
---
> Mais informações: <https://www.chromium.org/developers/how-tos/run-chromium-with-flags/>.

- Abre um arquivo:

```bash
chromium caminho/para/arquivo.html
```

- Abre uma URL:

```bash
chromium exemplo.com
```

- Abre no modo de navegação anônima (icognito):

```bash
chromium --incognito exemplo.com
```

- Abre em uma nova janela:

```bash
chromium --new-window exemplo.com
```

- Abre no modo app (Sem barra de tarefas, barra de URL, botões, etc.):

```bash
chromium --app='https://example.com'
```

- Usa um servidor proxy:

```bash
chromium --proxy-server="socks5://hostname:66" exemplo.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[alexsantee](mailto:40058461+alexsantee@users.noreply.github.com) | chromium: add pt_BR translation (#7167) | 2021-10-27T20:40:58 | [37494e617795](https://github.com/tldr-pages/tldr/commit/37494e617795bed2e46ff691ff1c0cfd085221b1)


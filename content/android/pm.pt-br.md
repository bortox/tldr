---
author: ['Rafael Julio']
date: 1634750076
title: "pm, TLDR Pages"
description: "pm, Executa ações e consultas em pacotes de apps instalados no dispositivo."
categories: "android"
---
> Mais informações: <https://developer.android.com/studio/command-line/adb#pm>.

- Exibe uma lista com todos os apps instalados:

```bash
pm list packages
```

- Exibe uma lista com todos os apps do sistema instalado:

```bash
pm list packages -s
```

- Exibe uma lista com todos os apps de terceiros instalados:

```bash
pm list packages -3
```

- Exibe uma lista com todos os apps cujos nomes estejam incluídos em palavras-chave:

```bash
pm list packages palavras_chave
```

- Exibe o caminho para o APK de um app:

```bash
pm path app
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Rafael Julio](mailto:development@rafifos.dev) | logcat, pm, settings, wm: add pt_BR translation (#7064) | 2021-10-20T19:14:36 | [fb1e0c85582d](https://github.com/tldr-pages/tldr/commit/fb1e0c85582da98e8c7816cd3a9c27f769ed19ba)


---
author: ['Bárbara Aliverti', 'git-em']
date: 1645867709
title: "am"
description: "am, Gerenciador de atividades do Android (Activity Manager)."
categories: "android"
---
> Mais informações: <https://developer.android.com/studio/command-line/adb#am>.

- Inicia uma activity específica:

```bash
am start -n com.android.settings/.Settings
```

- Inicia uma activity e passa dados para ela:

```bash
am start -a android.intent.action.VIEW -d tel:123
```

- Inicia uma activity correspondente a uma ação e categoria específicas:

```bash
am start -a android.intent.action.MAIN -c android.intent.category.HOME
```

- Converte uma intent em uma URI:

```bash
am to-uri -a android.intent.action.VIEW -d tel:123
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | am: fix pt_BR translation (#7817) | 2022-02-26T10:28:29 | [3610cc835884](https://github.com/tldr-pages/tldr/commit/3610cc83588482cebb89adf9732902c48da51b77)
[Bárbara Aliverti](mailto:64551613+barbaraaliverti@users.noreply.github.com) | am, bugreport, bugreportz, cmd: add pt_BR translation (#7058) | 2021-11-01T11:24:47 | [b93b30599135](https://github.com/tldr-pages/tldr/commit/b93b30599135a0927131d15dd4f13052b3810b29)


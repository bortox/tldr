---
author: ['Rafael Julio']
date: 1634750076
title: "logcat, TLDR Pages"
description: "logcat, Despeja um registro de mensagens do sistema."
categories: "android"
---
> Mais informações: <https://developer.android.com/studio/command-line/logcat>.

- Exibe a saída do registro:

```bash
logcat
```

- Salva a saída da mensagem de registro em um arquivo:

```bash
logcat -f caminho/para/arquivo
```

- Exibe apenas linhas em que a mensagem de registro corresponda a uma expressão regular:

```bash
logcat --regex expressao_regular
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Rafael Julio](mailto:development@rafifos.dev) | logcat, pm, settings, wm: add pt_BR translation (#7064) | 2021-10-20T19:14:36 | [fb1e0c85582d](https://github.com/tldr-pages/tldr/commit/fb1e0c85582da98e8c7816cd3a9c27f769ed19ba)


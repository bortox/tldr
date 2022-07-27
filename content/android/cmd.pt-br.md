---
author: ['Bárbara Aliverti']
date: 1635762287
title: "cmd, TLDR Pages"
description: "cmd, Gerenciador de serviços do Android (service manager)."
categories: "android"
---
> Mais informações: <https://cs.android.com/android/platform/superproject/+/master:frameworks/native/cmds/cmd/>.

- Lista todos os serviços em execução:

```bash
cmd -l
```

- Chama um serviço específico:

```bash
cmd alarm
```

- Chama um serviço com parâmetros:

```bash
cmd vibrator vibrate 300
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Bárbara Aliverti](mailto:64551613+barbaraaliverti@users.noreply.github.com) | am, bugreport, bugreportz, cmd: add pt_BR translation (#7058) | 2021-11-01T11:24:47 | [b93b30599135](https://github.com/tldr-pages/tldr/commit/b93b30599135a0927131d15dd4f13052b3810b29)


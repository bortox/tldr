---
author: ['FilipaDurao', 'bl-ue']
date: 1617130906
title: "at, TLDR Pages"
description: "at, Ferramenta para o agendamento de comandos."
categories: "common"
---
> O serviço atd (ou atrun) deve estar sendo executado para as atuais execuções.

> Mais informações: <https://man.archlinux.org/man/at.1>.

- Executar comandos da standard input em 5 minutos (pressionar `Ctrl + D`quando acabar):

```bash
at now + 5 minutes
```

- Executar um comando da standard input às 10:00 da manhã de hoje:

```bash
echo "./comando.sh" | at 1000
```

- Executar comandos de um dado arquivo na próxima terça:

```bash
at -f caminho/para/arquivo 9:30 PM Tue
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | at, atq, atrm, batch: add more information link (#5640) | 2021-03-30T21:01:46 | [f1da7db16065](https://github.com/tldr-pages/tldr/commit/f1da7db160655446057cf641b5339d2e9273bb7a)
[FilipaDurao](mailto:32716065+FilipaDurao@users.noreply.github.com) | at: add pt_BR translation (#3421) | 2019-10-18T18:17:42 | [76e3be9b54a1](https://github.com/tldr-pages/tldr/commit/76e3be9b54a1026aeba48eed02530c21ee41000c)


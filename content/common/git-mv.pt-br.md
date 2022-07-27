---
author: ['André Almeida', 'lucas schneider']
date: 1610111394
title: "git mv, TLDR Pages"
description: "git mv, Move ou renomeia arquivos e atualiza o index do Git."
categories: "common"
---
> Mais informações: <https://git-scm.com/docs/git-mv>.

- Move arquivos dentro de um repositório e adiciona no próximo commit:

```bash
git mv caminho/para/arquivo novo/caminho
```

- Renomeia um arquivo e adiciona a renomeação no próximo commit:

```bash
git mv nome_do_arquivo novo_nome
```

- Sobrescreve o arquivo no caminho alvo se ele já existir:

```bash
git mv --force arquivo alvo
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[André Almeida](mailto:andrealmeid@riseup.net) | git*: add pt_BR translation (#4688) | 2020-10-15T14:19:51 | [6264983e6980](https://github.com/tldr-pages/tldr/commit/6264983e69803c46fd45d86ecea6c79ea5f61104)


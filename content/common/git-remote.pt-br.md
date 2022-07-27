---
author: ['André Almeida']
date: 1602764391
title: "git remote, TLDR Pages"
description: "git remote, Gerencia repositórios monitorados ('remotes')."
categories: "common"
---
> Mais informações: <https://git-scm.com/docs/git-remote>.

- Mostre uma lista de remotes existentes, seus nomes e URL:

```bash
git remote -v
```

- Mostra infomação de um remote específico:

```bash
git remote show nome_do_remote
```

- Adiciona um remote:

```bash
git remote add nome_do_remote url_do_remote
```

- Muda a URL de um remote (use `--add` para manter a URL existente):

```bash
git remote set-url nome_do_remote nova_url
```

- Remove um remote:

```bash
git remote remove nome_do_remote
```

- Renomeia um remote:

```bash
git remote rename nome_antigo novo_nome
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[André Almeida](mailto:andrealmeid@riseup.net) | git*: add pt_BR translation (#4688) | 2020-10-15T14:19:51 | [6264983e6980](https://github.com/tldr-pages/tldr/commit/6264983e69803c46fd45d86ecea6c79ea5f61104)


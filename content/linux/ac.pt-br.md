---
author: ['Luis']
date: 1658401688
title: "ac, TLDR Pages"
description: "ac, Imprime estatísticas de quanto tempo usuários permaneceram conctados."
categories: "linux"
---
> Mais informações: <https://www.gnu.org/software/acct/manual/accounting.html#ac>.

- Imprime quanto tempo em horas o usuário atual ficou conectado:

```bash
ac
```

- Imprime quanto tempo em horas usuários ficaram conectados:

```bash
ac --individual-totals
```

- Imprime quanto tempo em horas um usuário em particular ficou conectado:

```bash
ac --individual-totals usuario
```

- Imprime quanto tempo um usuário em particular ficou conectado em horas por dia (com total):

```bash
ac --daily-totals --individual-totals usuario
```

- Também exibe detalhes adicionais:

```bash
ac --compatibility
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Luis](mailto:CasperBraske@users.noreply.github.com) | ac: add pt_BR translation (#8235) | 2022-07-21T13:08:08 | [e74e17d1a62c](https://github.com/tldr-pages/tldr/commit/e74e17d1a62c5bb56a0660c43e44323069521de5)


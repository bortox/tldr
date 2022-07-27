---
author: ['caduvieira']
date: 1633518566
title: "aws cur, TLDR Pages"
description: "aws cur, Cria, pesquisa e apaga relatórios de uso do AWS."
categories: "common"
---
> Mais informações: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/cur/index.html>.

- Cria um relatório de uso e custo do AWS definido de a partir de um arquivo JSON:

```bash
aws cur put-report-definition --report-definition file://caminho/para/definição_do_relatório.json
```

- Lista as definições dos relatórios de uso para a conta logada:

```bash
aws cur describe-report-definitions
```

- Apaga uma definição de relatório de uso:

```bash
aws cur --region região_aws delete-report-definition --report-name relatório
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[caduvieira](mailto:3831408+caduvieira@users.noreply.github.com) | aws-cur, aws-secretsmanager: add pt_BR translation (#6782) | 2021-10-06T13:09:26 | [02bb89332e0e](https://github.com/tldr-pages/tldr/commit/02bb89332e0e93a0f389de87567b10e50d5a63a1)


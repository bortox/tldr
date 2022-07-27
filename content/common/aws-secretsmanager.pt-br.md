---
author: ['caduvieira', 'lincc']
date: 1636372515
title: "aws secretsmanager, TLDR Pages"
description: "aws secretsmanager, Armazena, gerencia, e obtem secrets."
categories: "common"
---
> Mais informações: <https://docs.aws.amazon.com/cli/latest/reference/secretsmanager/>.

- Lista secrets armazenados pelo gerenciador de secretes na conta atual:

```bash
aws secretsmanager list-secrets
```

- Cria um secret:

```bash
aws secretsmanager create-secret --name nome --description "descrição_do_secret" --secret-string secret
```

- Apaga um secret:

```bash
aws secretsmanager delete-secret --secret-id nome_ou_arn
```

- Visualiza detalhes de um secret menos pelo texto do secret:

```bash
aws secretsmanager describe-secret --secret-id nome_ou_arn
```

- Obtẽm o valor do secret (para pegar a última versão do secret não use `--version-stage`):

```bash
aws secretsmanager get-secret-value --secret-id nome_ou_arn --version-stage versão_do_secret
```

- Alterna o secret imediatamente usando uma função Lambda:

```bash
aws secretsmanager rotate-secret --secret-id nome_ou_arn --rotation-lambda-arn arn_da_função_lambda
```

- Alterna o secret automaticamente a cada 30 dias usando uma função Lambda:

```bash
aws secretsmanager rotate-secret --secret-id nome_ou_arn --rotation-lambda-arn arn_da_função_lambda --rotation-rules AutomaticallyAfterDays=30
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: sync alias pages in translations (#6846) | 2021-11-08T12:55:15 | [d51f4893e973](https://github.com/tldr-pages/tldr/commit/d51f4893e973508f79168db1220c0556c9f88743)
[caduvieira](mailto:3831408+caduvieira@users.noreply.github.com) | aws-cur, aws-secretsmanager: add pt_BR translation (#6782) | 2021-10-06T13:09:26 | [02bb89332e0e](https://github.com/tldr-pages/tldr/commit/02bb89332e0e93a0f389de87567b10e50d5a63a1)


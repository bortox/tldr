---
author: ['258204']
date: 1623982539
title: "aws secretsmanager, TLDR Pages"
description: "aws secretsmanager, Store, manage, and retrieve secrets."
categories: "common"
---
> More information: <https://docs.aws.amazon.com/cli/latest/reference/secretsmanager/>.

- Show secrets stored by the secrets manager in the current account:

```bash
aws secretsmanager list-secrets
```

- Create a secret:

```bash
aws secretsmanager create-secret --name name --description "secret_description" --secret-string secret
```

- Delete a secret:

```bash
aws secretsmanager delete-secret --secret-id name_or_arn
```

- View details of a secret except for secret text:

```bash
aws secretsmanager describe-secret --secret-id name_or_arn
```

- Retrieve the value of a secret (to get the latest version of the secret omit `--version-stage`):

```bash
aws secretsmanager get-secret-value --secret-id name_or_arn --version-stage version_of_secret
```

- Rotate the secret immediately using a Lambda function:

```bash
aws secretsmanager rotate-secret --secret-id name_or_arn --rotation-lambda-arn arn_of_lambda_function
```

- Rotate the secret automatically every 30 days using a Lambda function:

```bash
aws secretsmanager rotate-secret --secret-id name_or_arn --rotation-lambda-arn arn_of_lambda_function --rotation-rules AutomaticallyAfterDays=30
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[258204](mailto:71364336+258204@users.noreply.github.com) | aws-secretsmanager: add page (#6131) Co-authored-by: Axel Navarro <navarroaxel@gmail.com> Co-authored-by: bl-ue <54780737+bl- [...] | 2021-06-18T04:15:39 | [99b5b6d5d72f](https://github.com/tldr-pages/tldr/commit/99b5b6d5d72fa92149a8618137dbc12d80ef309c)


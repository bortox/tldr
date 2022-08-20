---
author: ['Nicolas Hansse']
date: 1660918307
title: "aws lambda"
description: "aws lambda, CLI pour AWS lambda."
categories: "common"
---
> Plus d'informations : <https://docs.aws.amazon.com/cli/latest/reference/lambda/>.

- Lance une fonction :

```bash
aws lambda invoke --function-name nom chemin/vers/la/réponse.json
```

- Lance une fonction avec pour donnée d'entrée, un document JSON :

```bash
aws lambda invoke --function-name nom --payload json chemin/vers/la/réponse.json
```

- Liste les fonctions :

```bash
aws lambda list-functions
```

- Affiche la configuration d'une fonction :

```bash
aws lambda get-function-configuration --function-name nom
```

- Affiche les alias d'une fonction :

```bash
aws lambda list-aliases --function-name nom
```

- Affiche la configuration de concurrence pour une fonction :

```bash
aws lambda get-function-concurrency --function-name nom
```

- Affiche quel service AWS peut appeler une fonction :

```bash
aws lambda get-policy --function-name nom
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | aws-kinesis, aws-lambda: add French translation (#8374) | 2022-08-19T16:11:47 | [028208fe7cb9](https://github.com/tldr-pages/tldr/commit/028208fe7cb934773a956373e0d673d41b6772c2)


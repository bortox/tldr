---
author: ['Nicolas Hansse']
date: 1660918307
title: "aws kinesis"
description: "aws kinesis, CLI officiel d'AWS pour les services de streaming d'Amazon Kinesis."
categories: "common"
---
> Plus d'informations : <https://docs.aws.amazon.com/cli/latest/reference/kinesis/index.html#cli-aws-kinesis>.

- Affiche tous les streams du compte :

```bash
aws kinesis list-streams
```

- Écris une entrée dans le stream Kinesis :

```bash
aws kinesis put-record --stream-name nom --partition-key clé --data message_encodé_en_base64
```

- Écris une entrée dans le stream Kinesis avec un encodage base64 inline :

```bash
aws kinesis put-record --stream-name nom --partition-key clé --data "$( echo "mon message" | base64 )"
```

- Liste tous les fragments disponible dans un stream :

```bash
aws kinesis list-shards --stream-name nom
```

- Récupère un fragment pour lire depuis le plus vieux message dans la stream de ce dernier :

```bash
aws kinesis get-shard-iterator --shard-iterator-type TRIM_HORIZON --stream-name nom --shard-id id
```

- Lis les entrées d'un fragment en utilisant un itérateur de fragment :

```bash
aws kinesis get-records --shard-iterator itérateur
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | aws-kinesis, aws-lambda: add French translation (#8374) | 2022-08-19T16:11:47 | [028208fe7cb9](https://github.com/tldr-pages/tldr/commit/028208fe7cb934773a956373e0d673d41b6772c2)


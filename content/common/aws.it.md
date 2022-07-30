---
author: ['Franz', 'Marco Bonelli']
date: 1633438869
title: "aws"
description: "aws, Il tool da linea di comando ufficiale per Amazon Web Services."
categories: "common"
---
> Alcuni comandi aggiuntivi, come `aws s3`, hanno la propria documentazione.

> Maggiori informazioni: <https://aws.amazon.com/cli>.

- Lista tutti gli utenti IAM (Identity and Access Management):

```bash
aws iam list-users
```

- Lista tutte le instanze EC2 per una specifica regione:

```bash
aws ec2 describe-instances --region us-east-1
```

- Ricevi un messaggio da una specifica coda SQS:

```bash
aws sqs receive-message --queue-url https://queue.amazonaws.com/546123/Test
```

- Pubblica un messaggio SNS su uno specifico argomento:

```bash
aws sns publish --topic-arn arn:aws:sns:us-east-1:54633:Agomento --message "Message"
```

- Mostra la pagina di aiuto per uno specifico comando AWS:

```bash
aws comando help
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Franz](mailto:franz.f1032@gmail.com) | *: mention subcommands in Italian translation (#6804) | 2021-10-05T15:01:09 | [e13e67b1711e](https://github.com/tldr-pages/tldr/commit/e13e67b1711e4112cca0cc4d07521c0cf901290c)
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | aws: add Italian translation. | 2019-01-28T19:10:19 | [26f23f11101a](https://github.com/tldr-pages/tldr/commit/26f23f11101a965d5c6402b93f3deb788b69c83f)


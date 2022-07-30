---
author: ['Josa Gesell', 'pxgamer', 'Guido Lena Cota', 'Agniva De Sarker']
date: 1601832818
title: "msmtp"
description: "msmtp, An SMTP client."
categories: "common"
---
> It reads text from standard input and sends it to an SMTP server.

> More information: <https://marlam.de/msmtp>.

- Send an email using the default account configured in `~/.msmtprc`:

```bash
echo "Hello world" | msmtp to@example.org
```

- Send an email using a specific account configured in `~/.msmtprc`:

```bash
echo "Hello world" | msmtp --account=account_name to@example.org
```

- Send an email without a configured account. The password should be specified in the `~/.msmtprc` file:

```bash
echo "Hello world" | msmtp --host=localhost --port=999 --from=from@example.org to@example.org
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[pxgamer](mailto:owzie123@gmail.com) | msmtp: add link to homepage | 2019-06-04T21:29:40 | [733c01ae2194](https://github.com/tldr-pages/tldr/commit/733c01ae21944d915545fe4c6dd61b94c465abfe)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Adding clarity on how to enter the password | 2017-03-01T17:31:50 | [5426316b23b3](https://github.com/tldr-pages/tldr/commit/5426316b23b3602d76b3e3cd567a9d8862a31ef7)
[Josa Gesell](mailto:josa@gesell.me) | msmtp: add page | 2017-03-01T17:31:50 | [50d33b2cab24](https://github.com/tldr-pages/tldr/commit/50d33b2cab24b6b26db600d965c59f9c530581a1)


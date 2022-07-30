---
author: ['sitaramp', 'Lucas Gabriel Schneider', 'Guido Lena Cota', 'bl-ue', 'Sadeed']
date: 1633438245
title: "mail"
description: "mail, The command operates on the user's mailbox if no argument is given."
categories: "common"
---
> To send an email the message body is built from standard input.

> More information: <https://manned.org/mail>.

- Send a typed email message. The command-line below continues after pressing Enter key. Input CC email-id (optional) press Enter key. Input message text (can be multiline). Press Ctrl-D key to complete the message text:

```bash
mail --subject="subject line" to_user@example.com
```

- Send an email that contains file content:

```bash
mail --subject="$HOSTNAME filename.txt" to_user@example.com < path/to/filename.txt
```

- Send a `tar.gz` file as an attachment:

```bash
tar cvzf - path/to/directory1 path/to/directory2 | uuencode data.tar.gz | mail --subject="subject_line" to_user@example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sadeed](mailto:sadeeedw@gmail.com) | mail, mailx, mesg, mmv, monop, most, mscore: add link (#6795) | 2021-10-05T14:50:45 | [696b11611fa5](https://github.com/tldr-pages/tldr/commit/696b11611fa5c0ebd61d71d470fc2cd34b700f08)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | multiple pages: Use snake_case in token syntax (#4788) | 2020-11-01T14:40:05 | [0bb9c353a717](https://github.com/tldr-pages/tldr/commit/0bb9c353a717513283f8cda8493e5370ca47219a)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[sitaramp](mailto:2187750+sitaramp@users.noreply.github.com) | mail: add page (#2669) | 2019-09-16T19:03:43 | [b5ef37ff8c47](https://github.com/tldr-pages/tldr/commit/b5ef37ff8c4735d5c1edacb87a1482dda21bd09e)


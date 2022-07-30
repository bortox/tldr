---
author: ['Waldir Pimenta', 'Lucas Gabriel Schneider', 'luk3yx', 'syleung']
date: 1633351190
title: "sshpass"
description: "sshpass, An ssh password provider."
categories: "common"
---
> It works by creating a TTY, feeding the password into it, and then redirecting stdin to the ssh session.

> More information: <https://manned.org/sshpass>.

- Connect to a remote server using a password supplied on a file descriptor (in this case, stdin):

```bash
sshpass -d 0 ssh user@hostname
```

- Connect to a remote server with the password supplied as an option, and automatically accept unknown ssh keys:

```bash
sshpass -p password ssh -o StrictHostKeyChecking=no user@hostname
```

- Connect to a remote server using the first line of a file as the password, automatically accept unknown ssh keys, and launch a command:

```bash
sshpass -f file ssh -o StrictHostKeyChecking=no user@hostname "command"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | common/ssh*: add more information link (#6659) | 2021-10-04T14:39:50 | [a092be52d7de](https://github.com/tldr-pages/tldr/commit/a092be52d7ded26ec56154160c90900c6338e76d)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[luk3yx](mailto:luk3yx@users.noreply.github.com) | sshpass: remove unmatched quote mark (#1413) | 2017-06-19T00:27:11 | [0fbce892d828](https://github.com/tldr-pages/tldr/commit/0fbce892d82858d37137da77250977ce08659ba2)
[luk3yx](mailto:luk3yx@users.noreply.github.com) | sshpass: add page (#1411) | 2017-06-18T21:12:00 | [f507c8185720](https://github.com/tldr-pages/tldr/commit/f507c8185720683e87bd87cfb9a68c529de27906)


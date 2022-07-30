---
author: ['Waldir Pimenta', 'Owen Voke', 'Lucas Gabriel Schneider']
date: 1612112718
title: "msg"
description: "msg, Send a message to a specific user or session."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/msg>.

- Send a message to a specified user or session:

```bash
msg username|session_name|session_id message
```

- Send a message from stdin:

```bash
echo "message" | msg username|session_name|session_id
```

- Send a message to a specific server:

```bash
msg /server:server_name username|session_name|session_id
```

- Send a message to all users of the current machine:

```bash
msg *
```

- Set a delay in seconds for a message:

```bash
msg /time:seconds
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Owen Voke](mailto:owzie123@gmail.com) | msg: add page (#2174) | 2018-07-11T17:23:08 | [39f4ffc68f05](https://github.com/tldr-pages/tldr/commit/39f4ffc68f05475d558e29f6e9f14bc8eca2b894)


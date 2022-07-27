---
author: ['Lucas Gabriel Schneider', 'marchersimon', 'Saif Azmi']
date: 1618869951
title: "gpg-zip, TLDR Pages"
description: "gpg-zip, Encrypt files and directories in an archive using GPG."
categories: "common"
---
> More information: <https://www.gnupg.org/documentation/manuals/gnupg/gpg_002dzip.html>.

- Encrypt a directory into `archive.gpg` using a passphrase:

```bash
gpg-zip --symmetric --output archive.gpg path/to/directory
```

- Decrypt `archive.gpg` into a directory of the same name:

```bash
gpg-zip --decrypt path/to/archive.gpg
```

- List the contents of the encrypted `archive.gpg`:

```bash
gpg-zip --list-archive path/to/archive.gpg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Saif Azmi](mailto:saif.azmi0108@gmail.com) | gpg-zip: add page (#2392) | 2018-10-06T00:37:28 | [f7b073cc4950](https://github.com/tldr-pages/tldr/commit/f7b073cc49507e3da91681feb541710eda8ab896)


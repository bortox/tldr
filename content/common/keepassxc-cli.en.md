---
author: ['Stig124']
date: 1625042457
title: "keepassxc-cli, TLDR Pages"
description: "keepassxc-cli, Command-line interface for KeepassXC."
categories: "common"
---
> More information: <https://manned.org/keepassxc-cli>.

- Search entries:

```bash
keepassxc-cli lookup path/to/database_file name
```

- List the contents of a folder:

```bash
keepassxc-cli ls path/to/database_file /path/to/directory
```

- Add an entry with an auto-generated password:

```bash
keepassxc-cli add --generate path/to/database_file entry_name
```

- Delete an entry:

```bash
keepassxc-cli rm path/to/database_file entry_name
```

- Copy an entry's password to the clipboard:

```bash
keepassxc-cli clip path/to/database_file entry_name
```

- Copy a TOTP code to the clipboard:

```bash
keepassxc-cli clip --totp path/to/database_file entry_name
```

- Generate a passphrase with 7 words:

```bash
keepassxc-cli diceware --words 7
```

- Generate a password with 16 printable ASCII characters:

```bash
keepassxc-cli generate --lower --upper --numeric --special --length 16
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | keepassxc-cli: add page (#6071) | 2021-06-30T10:40:57 | [5bacde463d92](https://github.com/tldr-pages/tldr/commit/5bacde463d927844e26f5e63517d3deda7f29152)


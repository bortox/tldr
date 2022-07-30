---
author: ['Owen Voke', 'Bharadwaj Raju', 'Marco Bonelli', 'bl-ue', 'marchersimon']
date: 1658125216
title: "zsh"
description: "zsh, Z SHell, a Bash-compatible command-line interpreter."
categories: "common"
---
> See also `histexpand` for history expansion.

> More information: <https://www.zsh.org>.

- Start an interactive shell session:

```bash
zsh
```

- Execute a command and then exit:

```bash
zsh -c "command"
```

- Execute a script:

```bash
zsh path/to/script.zsh
```

- Execute a script, printing each command before executing it:

```bash
zsh --xtrace path/to/script.zsh
```

- Start an interactive shell session in verbose mode, printing each command before executing it:

```bash
zsh --verbose
```

- Execute a specific command inside `zsh` with disabled glob patterns:

```bash
noglob command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | zsh: add noglob example (#8179) * zsh: add noglob example Co-authored-by: Muhammad Falak R Wani <falakreyaz@gmail.com> | 2022-07-18T08:20:16 | [30ec44ef4352](https://github.com/tldr-pages/tldr/commit/30ec44ef43522640943b204954dcd298f1e434e4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | bash, dash, fish, ksh, rbash, sh, zsh: refresh (#5714) | 2021-04-14T16:07:21 | [16e4ed5c8993](https://github.com/tldr-pages/tldr/commit/16e4ed5c899393a2563346ddde246e136de801ab)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | histexpand: add page (#5455) Also add a reference to the new page in bash.md and zsh.md | 2021-04-04T22:07:13 | [03819122c9bc](https://github.com/tldr-pages/tldr/commit/03819122c9bc668750cd8c9a7f8a4a92c615c0e3)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | multiple pages: add homepages (#3026) * zstd: add link to homepage * zsh: add link to homepage * zopflipng: add link to homepage * [...] | 2019-05-14T18:09:07 | [c4e95b92c42f](https://github.com/tldr-pages/tldr/commit/c4e95b92c42fe9fe8428c8d7c8cd5ad8d0bd1b0b)
[Bharadwaj Raju](mailto:bharadwaj.raju777@gmail.com) | Add page for zsh | 2016-02-19T17:53:19 | [8f95eaa45db9](https://github.com/tldr-pages/tldr/commit/8f95eaa45db93069f018b849be85c86729855a46)


---
author: ['Waldir Pimenta', 'pxgamer', 'Emily Grace Seville', 'Ruben Vereecken', 'bl-ue', 'Quentin Duchemin', 'Starbeamrainbowlabs', 'sabour_f', 'Hayden Schiff', 'David Menéndez Negro', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1660870417
title: "bash"
description: "bash, Bourne-Again SHell, an `sh`-compatible command-line interpreter."
categories: "common"
---
> See also: `zsh`, `histexpand` (history expansion).

> More information: <https://gnu.org/software/bash/>.

- Start an interactive shell session:

```bash
bash
```

- Start an interactive shell session without loading startup configs:

```bash
bash --norc
```

- Execute specific [c]ommands:

```bash
bash -c "echo 'bash is executed'"
```

- Execute a specific script:

```bash
bash path/to/script.sh
```

- Execute a specific script while printing each command before executing it:

```bash
bash -x path/to/script.sh
```

- Execute a specific script and stop at the first [e]rror:

```bash
bash -e path/to/script.sh
```

- Execute specific commands from stdin:

```bash
echo "echo 'bash is executed'" | bash
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | bash: refresh page (#7980) * Refresh a page: - better grammar - better token syntax * Simplify `-s` example | 2022-08-19T02:53:37 | [e7eae6c77237](https://github.com/tldr-pages/tldr/commit/e7eae6c77237142902d2dfee3da821cac8e1ae01)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | bash, dash, fish, ksh, rbash, sh, zsh: refresh (#5714) | 2021-04-14T16:07:21 | [16e4ed5c8993](https://github.com/tldr-pages/tldr/commit/16e4ed5c899393a2563346ddde246e136de801ab)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | histexpand: add page (#5455) Also add a reference to the new page in bash.md and zsh.md | 2021-04-04T22:07:13 | [03819122c9bc](https://github.com/tldr-pages/tldr/commit/03819122c9bc668750cd8c9a7f8a4a92c615c0e3)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[David Menéndez Negro](mailto:dmnq@hotmail.es) | bash: clarify print version example description (#4730) | 2020-10-19T18:50:30 | [1ce8ecd6ed17](https://github.com/tldr-pages/tldr/commit/1ce8ecd6ed178dde7d3a9c05f54c8c90e964fb9a)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[pxgamer](mailto:owzie123@gmail.com) | bash: add link to homepage | 2019-06-09T18:53:49 | [a6c02066dc74](https://github.com/tldr-pages/tldr/commit/a6c02066dc74fd2da3ffbf0f8fd0f050c3e553e5)
[Quentin Duchemin](mailto:quentinduchemin@tuta.io) | bash: add -e option (#2723) | 2019-01-23T07:27:08 | [c3d16cdf9ad7](https://github.com/tldr-pages/tldr/commit/c3d16cdf9ad7d96e0c6c7478b202e0b195f5c91d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | bash: add debugging example (#1493) | 2017-09-21T09:35:20 | [cd5897c7c75a](https://github.com/tldr-pages/tldr/commit/cd5897c7c75ab7ad54c6bcc91a65084756819251)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | bash: quote command passed with -c | 2016-09-04T21:59:10 | [0f16059d3a6c](https://github.com/tldr-pages/tldr/commit/0f16059d3a6ca27c2cba97c39460335a72a71b96)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | bash: add --version | 2016-09-01T15:31:38 | [9ecfc2bd9dcb](https://github.com/tldr-pages/tldr/commit/9ecfc2bd9dcb5d75a74e86894b6d1c405ddb77c6)
[Hayden Schiff](mailto:oxguy3@gmail.com) | bash: parity with `sh` | 2016-02-23T02:14:41 | [8aaaec66c127](https://github.com/tldr-pages/tldr/commit/8aaaec66c127ffbc510743fc3a2f951548945bd0)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[sabour_f](mailto:sabour_f@epitech.eu) | bash: add page | 2016-01-05T01:33:17 | [01ab02d1eff7](https://github.com/tldr-pages/tldr/commit/01ab02d1eff7c0739617af79d733a3236e58dca6)


---
author: ['Marco Bonelli', 'Ruben Vereecken', 'Igor Shubovych', 'Ignacio Mattos', 'SirGlorg', 'bl-ue', 'marchersimon', 'Mateusz Konieczny']
date: 1624998369
title: "history, TLDR Pages"
description: "history, Command-line history."
categories: "common"
---
> More information: <https://www.gnu.org/software/bash/manual/html_node/Bash-History-Builtins.html>.

- Display the commands history list with line numbers:

```bash
history
```

- Display the last 20 commands (in `zsh` it displays all commands starting from the 20th):

```bash
history 20
```

- Clear the commands history list (only for current `bash` shell):

```bash
history -c
```

- Overwrite history file with history of current `bash` shell (often combined with `history -c` to purge history):

```bash
history -w
```

- Delete the history entry at the specified offset:

```bash
history -d offset
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | history: add note for zsh (#6110) | 2021-06-29T22:26:09 | [e64cd91d5b00](https://github.com/tldr-pages/tldr/commit/e64cd91d5b00ae1e0604c24411776eaedb86f09e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | histexpand, history: add Spanish translation (#5825) | 2021-04-24T04:14:43 | [d8a8f653ec27](https://github.com/tldr-pages/tldr/commit/d8a8f653ec27a521dc4e079f58fd2dba621e5170)
[SirGlorg](mailto:sirglorg@gmail.com) | history: list last n commands from the history (#4138) * Added history command sample * Update pages/common/history.md Co-authored-by: [...] | 2020-07-01T12:46:09 | [fee169f50ca1](https://github.com/tldr-pages/tldr/commit/fee169f50ca128716896b3c33fc94af9629d412f)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | history: add one example. | 2019-01-11T01:53:19 | [cf225aca7af5](https://github.com/tldr-pages/tldr/commit/cf225aca7af5bcb97bd1912af913c2565230c886)
[Mateusz Konieczny](mailto:matkoniecz@gmail.com) | shorten history -c explanation using suggestion by @waldyrious | 2016-03-19T21:09:30 | [aab6d79c96c0](https://github.com/tldr-pages/tldr/commit/aab6d79c96c0dcd0ecb0c497bbb69074a524f8cd)
[Mateusz Konieczny](mailto:matkoniecz@gmail.com) | add explanation how to fully erase bash shell history based on http://unix.stackexchange.com/questions/203290/how-do-i-clear-the- [...] | 2016-03-15T19:12:27 | [9cc107138dfb](https://github.com/tldr-pages/tldr/commit/9cc107138dfb5073bcbe2aab058c3897be22d4c8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | history: explain that 'history -c' relates only to bash | 2015-12-10T21:39:13 | [7c4ed711033e](https://github.com/tldr-pages/tldr/commit/7c4ed711033ef9c504223f674df0757c02a56fd4)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | history: fix grammar | 2015-12-09T21:42:04 | [3f23333353b9](https://github.com/tldr-pages/tldr/commit/3f23333353b928c96a1ee590d0aee8b6f9dd08a9)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Add history | 2015-11-22T22:40:47 | [1b53fda2a05b](https://github.com/tldr-pages/tldr/commit/1b53fda2a05ba49081b8c8feb3ff3a3a69a7d6c6)


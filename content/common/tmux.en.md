---
author: ['Waldir Pimenta', 'egilkh', 'Nuno Agostinho', 'Hay Kranen', 'pxgamer', 'Ryan Olson', 'Marco Bonelli', 'Ruben Vereecken', 'Lyuben Petrov', 'Muhammad Falak R Wani']
date: 1633872101
title: "tmux"
description: "tmux, Terminal multiplexer. It allows multiple sessions with windows, panes, and more."
categories: "common"
---
> See also `zellij` and `screen`.

> More information: <https://github.com/tmux/tmux>.

- Start a new session:

```bash
tmux
```

- Start a new named session:

```bash
tmux new -s name
```

- List existing sessions:

```bash
tmux ls
```

- Attach to the most recently used session:

```bash
tmux attach
```

- Detach from the current session (inside a tmux session):

```bash
Ctrl-B d
```

- Create a new window (inside a tmux session):

```bash
Ctrl-B c
```

- Switch between sessions and windows (inside a tmux session):

```bash
Ctrl-B w
```

- Kill a session by name:

```bash
tmux kill-session -t name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | tmux: add see also pages (#6859) | 2021-10-10T15:21:41 | [b87bbaf2296e](https://github.com/tldr-pages/tldr/commit/b87bbaf2296e16b883571920d0227ef4612146d8)
[Nuno Agostinho](mailto:nunodanielagostinho@gmail.com) | tmux: add window management commands and small improvements (#4953) | 2020-11-21T03:55:15 | [166688ddeb5b](https://github.com/tldr-pages/tldr/commit/166688ddeb5b01323b5827abcd13a9161e43a791)
[Ryan Olson](mailto:ryanolsonx@gmail.com) | Tmux improvements (#3806) As it's in the tmux tldr, we don't need to mention tmux when talking about a tmux session. Cleaned up some [...] | 2020-02-12T12:48:30 | [8169ae1edc15](https://github.com/tldr-pages/tldr/commit/8169ae1edc15835b61d7a57d79236628428dbe46)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | tmux: add link to homepage | 2019-05-14T19:58:59 | [a16205659979](https://github.com/tldr-pages/tldr/commit/a16205659979be2f9d43604cb0814e297aa97096)
[Hay Kranen](mailto:huskyr@gmail.com) | tmux: adding how to kill a session when attached (#1940) | 2018-01-27T09:16:07 | [235f69857e40](https://github.com/tldr-pages/tldr/commit/235f69857e406a4b51c8c4f106925c3c51a7a944)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | change all keyboard shortcuts to have spaces around the + sign (#1356) | 2017-04-29T00:34:51 | [433370e2ad4c](https://github.com/tldr-pages/tldr/commit/433370e2ad4c946240af47231397315eb803695f)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | standardize format of keyboard shortcuts (#1354) * fix capitalization of keyboard shortcuts (elinks, tmux, screen) * adjust formatting [...] | 2017-04-28T09:44:50 | [7e1f06ade4d8](https://github.com/tldr-pages/tldr/commit/7e1f06ade4d869f8c1690fd04c25d8476c46b198)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[egilkh](mailto:egilkh@users.noreply.github.com) | Fix missing backticks Added some backticks that where missing. | 2014-11-04T14:44:44 | [3acb4dc447df](https://github.com/tldr-pages/tldr/commit/3acb4dc447df7188b78a64b25b6046eb1e137083)
[Lyuben Petrov](mailto:lyuben.y.petrov@gmail.com) | Add tmux | 2014-11-02T13:13:40 | [d63d1a7b3172](https://github.com/tldr-pages/tldr/commit/d63d1a7b31724ae9fd969628b9502d458cd26f3f)


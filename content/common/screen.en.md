---
author: ['Waldir Pimenta', 'Srinivasan R', 'lord63', 'rprieto', 'snollygolly', 'HairyFotr', 'Blake Bourque', 'Ruben Vereecken', 'Muhammad Falak R Wani', 'Beshr Al Nahas', 'Daniel Senff', 'Michael Miller', 'Lucas Gabriel Schneider']
date: 1633786725
title: "screen, TLDR Pages"
description: "screen, Hold a session open on a remote server. Manage multiple windows with a single SSH connection."
categories: "common"
---
> See also `tmux` and `zellij`.

> More information: <https://manned.org/screen>.

- Start a new screen session:

```bash
screen
```

- Start a new named screen session:

```bash
screen -S session_name
```

- Start a new daemon and log the output to `screenlog.x`:

```bash
screen -dmLS session_name command
```

- Show open screen sessions:

```bash
screen -ls
```

- Reattach to an open screen:

```bash
screen -r session_name
```

- Detach from inside a screen:

```bash
Ctrl + A, D
```

- Kill the current screen session:

```bash
Ctrl + A, K
```

- Kill a detached screen:

```bash
screen -X -S session_name quit
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | screen: add more information link (#6858) | 2021-10-09T15:38:45 | [c80f4c3ccb6e](https://github.com/tldr-pages/tldr/commit/c80f4c3ccb6e52e54b078f747271efc0eba13f4b)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Michael Miller](mailto:miketm89@gmail.com) | screen: add kill current session example (#3078) | 2019-06-14T19:02:28 | [d96ae8af1fef](https://github.com/tldr-pages/tldr/commit/d96ae8af1fef3f9101e20b0a2580d2eabcfa228f)
[HairyFotr](mailto:hairyfotr@gmail.com) | Fix a few typos | 2017-07-23T16:22:44 | [e0ccb7147a25](https://github.com/tldr-pages/tldr/commit/e0ccb7147a25b5d738e3991f399f87e45f3a4140)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | change all keyboard shortcuts to have spaces around the + sign (#1356) | 2017-04-29T00:34:51 | [433370e2ad4c](https://github.com/tldr-pages/tldr/commit/433370e2ad4c946240af47231397315eb803695f)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | standardize format of keyboard shortcuts (#1354) * fix capitalization of keyboard shortcuts (elinks, tmux, screen) * adjust formatting [...] | 2017-04-28T09:44:50 | [7e1f06ade4d8](https://github.com/tldr-pages/tldr/commit/7e1f06ade4d869f8c1690fd04c25d8476c46b198)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | screen.md: fix typo | 2016-06-21T01:07:51 | [2e95ede47985](https://github.com/tldr-pages/tldr/commit/2e95ede4798586abd99556d82c5188e6ed4fe55d)
[Beshr Al Nahas](mailto:beshr.ns@gmail.com) | screen: Start a new deamon and log the output (#912) | 2016-06-21T01:06:49 | [7870c6c4c7aa](https://github.com/tldr-pages/tldr/commit/7870c6c4c7aa58e4dbb30e88fc496362976b4745)
[Daniel Senff](mailto:mail@danielsenff.de) | Update screen.md (#862) session name is also the session id, so have the same wording | 2016-05-17T11:56:39 | [d2de67f45b32](https://github.com/tldr-pages/tldr/commit/d2de67f45b32e4cc51247784da7d2a2f3c86e093)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[snollygolly](mailto:snollygolly@gmail.com) | added kill detached screen command | 2015-12-29T04:20:38 | [d143af0cbb04](https://github.com/tldr-pages/tldr/commit/d143af0cbb04c4b10730c1abd3817f91f74b7d32)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Blake Bourque](mailto:Techplex.Engineer@gmail.com) | Add another common use case for named sessions | 2015-06-26T04:12:09 | [d5711a950785](https://github.com/tldr-pages/tldr/commit/d5711a950785f13d44d630ad08fd29cd0321e6fc)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)


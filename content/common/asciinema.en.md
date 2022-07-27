---
author: ['Marco Bonelli', 'Schneider', 'Waldir Pimenta']
date: 1559564381
title: "asciinema, TLDR Pages"
description: "asciinema, Record and replay terminal sessions, and optionally share them on asciinema.org."
categories: "common"
---
> More information: <https://asciinema.org/>.

- Associate the local install of `asciinema` with an asciinema.org account:

```bash
asciinema auth
```

- Make a new recording (once finished, user will be prompted to upload it or save it locally):

```bash
asciinema rec
```

- Make a new recording and save it to a local file:

```bash
asciinema rec path/to/file.cast
```

- Replay a terminal recording from a local file:

```bash
asciinema play path/to/file.cast
```

- Replay a terminal recording hosted on asciinema.org:

```bash
asciinema play https://asciinema.org/a/cast_id
```

- Make a new recording, limiting any idle time to at most 2.5 seconds:

```bash
asciinema rec -i 2.5
```

- Print the full output of a locally saved recording:

```bash
asciinema cat path/to/file.cast
```

- Upload a locally saved terminal session to asciinema.org:

```bash
asciinema upload path/to/file.cast
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | asciinema.md: add homepage | 2019-04-12T14:41:22 | [cf881fb0280f](https://github.com/tldr-pages/tldr/commit/cf881fb0280fa8fc5821f671a54cb6a6b989d846)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | asciinema: add page (#2564) | 2018-11-12T11:17:37 | [be10465d2f96](https://github.com/tldr-pages/tldr/commit/be10465d2f96dbf862019099314d88d85bd72d4c)


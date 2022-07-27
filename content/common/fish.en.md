---
author: ['Alexandros Kotzias', 'Samruddhi Somani', 'Cam.Rossington.debsrv', 'Emily Grace Seville', 'pxgamer', 'bl-ue']
date: 1654675771
title: "fish, TLDR Pages"
description: "fish, The Friendly Interactive SHell, a command-line interpreter designed to be user friendly."
categories: "common"
---
> More information: <https://fishshell.com>.

- Start an interactive shell session:

```bash
fish
```

- Start an interactive shell session without loading startup configs:

```bash
fish --no-config
```

- Execute specific commands:

```bash
fish --command "echo 'fish is executed'"
```

- Execute a specific script:

```bash
fish path/to/script.fish
```

- Check a specific script for syntax errors:

```bash
fish --no-execute path/to/script.fish
```

- Execute specific commands from stdin:

```bash
echo "echo 'fish is executed'" | fish
```

- Start an interactive shell session in private mode, where the shell does not access old history or save new history:

```bash
fish --private
```

- Define and export an environmental variable that persists across shell restarts (builtin):

```bash
set --universal --export variable_name variable_value
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | fish: refresh page (#7987) * Refresh a page: - better grammar - better token syntax * Add reading commands from stdin sample | 2022-06-08T10:09:31 | [57aac78e0d1b](https://github.com/tldr-pages/tldr/commit/57aac78e0d1b7f1b7969db6a63cad767ad0bf6b7)
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | fish: update page (#7415) * fish tldr clean-up: - short options preferred over long ones - page made more consistent with elvish page [...] | 2021-11-25T21:46:27 | [b3cd39d9b650](https://github.com/tldr-pages/tldr/commit/b3cd39d9b6502da310d214f1a5a938a44e131b99)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | bash, dash, fish, ksh, rbash, sh, zsh: refresh (#5714) | 2021-04-14T16:07:21 | [16e4ed5c8993](https://github.com/tldr-pages/tldr/commit/16e4ed5c899393a2563346ddde246e136de801ab)
[Samruddhi Somani](mailto:samruddhisomani@users.noreply.github.com) | fish: add example for environment variables (#3338) | 2019-10-07T18:55:45 | [af27d2f96a67](https://github.com/tldr-pages/tldr/commit/af27d2f96a67dcf136f3ed58b442c681b2af2ddf)
[pxgamer](mailto:owzie123@gmail.com) | fish: add link to homepage | 2019-06-07T23:58:59 | [3f27858b8005](https://github.com/tldr-pages/tldr/commit/3f27858b80052320bbc93cdf4cabe74f4c602505)
[Alexandros Kotzias](mailto:alexandroskotzias@gmail.com) | fish: fix typo | 2018-02-20T08:38:46 | [7b35426ff00a](https://github.com/tldr-pages/tldr/commit/7b35426ff00af09524b992f348030745a5b6b643)
[Cam.Rossington.debsrv](mailto:deoxys314@gmail.com) | Changed wording on --no-execute to read more cleanly. | 2018-01-06T03:19:37 | [95372fdd56aa](https://github.com/tldr-pages/tldr/commit/95372fdd56aace95d7232af66352b674923d1c0e)
[Cam.Rossington.debsrv](mailto:deoxys314@gmail.com) | Added period to end of description. This change is made to comply with formatting guidelines for the project. | 2018-01-03T05:36:52 | [b319373dabb5](https://github.com/tldr-pages/tldr/commit/b319373dabb5ef4c3d247b46538ccecb66c4b802)
[Cam.Rossington.debsrv](mailto:deoxys314@gmail.com) | Made changes suggested by agnivade. | 2018-01-03T05:34:17 | [7a1992c4c108](https://github.com/tldr-pages/tldr/commit/7a1992c4c10836fd93fb836117c4fb4234f73f63)
[Cam.Rossington.debsrv](mailto:deoxys314@gmail.com) | Changed command description to match standards. | 2018-01-02T23:37:35 | [a2389f17d30a](https://github.com/tldr-pages/tldr/commit/a2389f17d30a3462209b42f26d5e65ac9dfb1510)
[Cam.Rossington.debsrv](mailto:deoxys314@gmail.com) | fish: add page Added the fish shell. Information included was based on other shells, notably bash. | 2018-01-02T19:00:12 | [928ff1b87321](https://github.com/tldr-pages/tldr/commit/928ff1b873213f9927c29d757305eabe0f39489e)


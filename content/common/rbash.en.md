---
author: ['bl-ue', 'sadboyzvone', 'Starbeamrainbowlabs', 'Agniva De Sarker']
date: 1618409241
title: "rbash"
description: "rbash, Restricted Bash shell, equivalent to `bash --restricted`."
categories: "common"
---
> Does not permit changing the working directory, redirecting command output, or modifying environment variables, among other things.

> See also `histexpand` for history expansion.

> More information: <https://www.gnu.org/software/bash/manual/html_node/The-Restricted-Shell>.

- Start an interactive shell session:

```bash
rbash
```

- Execute a command and then exit:

```bash
rbash -c "command"
```

- Execute a script:

```bash
rbash path/to/script.sh
```

- Execute a script, printing each command before executing it:

```bash
rbash -x path/to/script.sh
```

- Execute commands from a script, stopping at the first error:

```bash
rbash -e path/to/script.sh
```

- Read and execute commands from stdin:

```bash
rbash -s
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | bash, dash, fish, ksh, rbash, sh, zsh: refresh (#5714) | 2021-04-14T16:07:21 | [16e4ed5c8993](https://github.com/tldr-pages/tldr/commit/16e4ed5c899393a2563346ddde246e136de801ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Teensy grammatical fix | 2017-11-21T00:07:54 | [ea57113b12b5](https://github.com/tldr-pages/tldr/commit/ea57113b12b5c6ef4800fa63092a99793252f150)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Simplified heading | 2017-11-20T19:46:13 | [8edaf808cadc](https://github.com/tldr-pages/tldr/commit/8edaf808cadc401ab2e215b296d3f1fd731e61c5)
[sadboyzvone](mailto:zvonimirurdinski@protonmail.ch) | rbash: remove some restrictions | 2017-11-17T16:39:15 | [0f1e8052e978](https://github.com/tldr-pages/tldr/commit/0f1e8052e978811b40793159d5f37654eca6ceaf)
[sadboyzvone](mailto:zvonimirurdinski@protonmail.ch) | rbash: put restrictions onto 1 line | 2017-11-17T16:37:36 | [ff781ee8f04f](https://github.com/tldr-pages/tldr/commit/ff781ee8f04fd98a42c1966eb0e4ab8ec7fdfa85)
[sadboyzvone](mailto:zvonimirurdinski@protonmail.ch) | rbash: fix for lint | 2017-11-16T22:46:57 | [373bdf198262](https://github.com/tldr-pages/tldr/commit/373bdf198262f0080b04f6c756b6fbfd7854236f)
[sadboyzvone](mailto:zvonimirurdinski@protonmail.ch) | rbash: add page | 2017-11-16T22:40:05 | [4dc0202460d5](https://github.com/tldr-pages/tldr/commit/4dc0202460d52122b209c0fa03f5d31551820a1c)


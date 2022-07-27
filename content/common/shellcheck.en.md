---
author: ['Marco Bonelli', 'Penghe Geng', 'bl-ue', 'Starbeamrainbowlabs']
date: 1618578912
title: "shellcheck, TLDR Pages"
description: "shellcheck, Shell script static analysis tool."
categories: "common"
---
> Check shell scripts for errors, usage of deprecated/insecure features, and bad practices.

> More information: <https://www.shellcheck.net>.

- Check a shell script:

```bash
shellcheck path/to/script.sh
```

- Check a shell script interpreting it as the specified shell dialect (overrides the shebang at the top of the script):

```bash
shellcheck --shell sh|bash|dash|ksh path/to/script.sh
```

- Ignore one or more error types:

```bash
shellcheck --exclude SC1009,SC1073 path/to/script.sh
```

- Also check any sourced shell scripts:

```bash
shellcheck --checked-sourced path/to/script.sh
```

- Display output in the specified format (defaults to `tty`):

```bash
shellcheck --format tty|checkstyle|diff|gcc|json|json1|quiet path/to/script.sh
```

- Enable one or more optional checks:

```bash
shellcheck --enable=add-default-case|avoid-nullary-conditions
```

- List all available optional checks that are disabled by default:

```bash
shellcheck --list-optional
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | shellcheck: refresh (#5746) | 2021-04-16T15:15:12 | [250c33590eb7](https://github.com/tldr-pages/tldr/commit/250c33590eb77aa3ae88b8321dc2cae3f0d27963)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "multiple pages: add homepages" This reverts commit 347e5573036e13b360b81a3f9f1bad75cf2c2b03. | 2018-12-20T00:33:18 | [45ec3033c04f](https://github.com/tldr-pages/tldr/commit/45ec3033c04fbc67b97fa4d21e2b409b1f14a667)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages | 2018-12-20T00:29:00 | [347e5573036e](https://github.com/tldr-pages/tldr/commit/347e5573036e13b360b81a3f9f1bad75cf2c2b03)
[Penghe Geng](mailto:gpenghe@gmail.com) | shellcheck: add page (#2140) | 2018-06-20T13:12:26 | [60a0f9d1a5cb](https://github.com/tldr-pages/tldr/commit/60a0f9d1a5cbc03afd20a8e4ca94d965c8bb8a4e)


---
author: ['marchersimon', 'Emily Grace Seville', 'Agniva De Sarker', 'Waldir Pimenta', 'git-em']
date: 1660524792
title: "ed"
description: "ed, The original Unix text editor."
categories: "common"
---
> See also: `awk`, `sed`.

> More information: <https://www.gnu.org/software/ed/manual/ed_manual.html>.

- Start an interactive editor session with an empty document:

```bash
ed
```

- Start an interactive editor session with an empty document and a specific prompt:

```bash
ed --prompt='> '
```

- Start an interactive editor session with user-friendly errors:

```bash
ed --verbose
```

- Start an interactive editor session with an empty document and without diagnostics, byte counts and '!' prompt:

```bash
ed --quiet
```

- Start an interactive editor session without exit status change when command fails:

```bash
ed --loose-exit-status
```

- Edit a specific file (this shows the byte count of the loaded file):

```bash
ed path/to/file
```

- Replace a string with a specific replacement for all lines:

```bash
,s/regular_expression/replacement/g
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | ed: refresh/add pages (#7933) * Update common/ed.md * Create osx/ed.md * Prefer `a specific` * Fix quoting in common/ed * Fix quoting [...] | 2022-08-15T02:53:12 | [e6fb17a014ba](https://github.com/tldr-pages/tldr/commit/e6fb17a014baf52f06f9171f16eff7e79fa62373)
[git-em](mailto:56173216+git-em@users.noreply.github.com) | common/*: replace man.archlinux.org (#7860) | 2022-03-09T05:28:57 | [a48819f19092](https://github.com/tldr-pages/tldr/commit/a48819f19092a82a1faef1f9f105bc1eb27d2df7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | ed: add link (#5532) | 2021-03-29T18:34:34 | [609014c1978e](https://github.com/tldr-pages/tldr/commit/609014c1978e51d6b5872b3b47c3000f732a0f21)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | add ed.md (#944) * add ed.md inspired by this very nice introductory blog post: https://sanctum.geek.nz/arabesque/actually-using-ed/ * [...] | 2016-07-10T11:59:29 | [fff4a4c95e57](https://github.com/tldr-pages/tldr/commit/fff4a4c95e57f0e1742984caa66996255149e1cd)


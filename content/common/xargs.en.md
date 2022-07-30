---
author: ['Waldir Pimenta', 'Igor Shubovych', 'Agniva De Sarker', 'Alex Flores', 'okaymaged', 'TiredSounds', 'Balázs Úr', 'Andrei Cioara', 'syleung', 'Sahil Bajaj', 'Leandro Ostera', 'Florian Leitner']
date: 1633350747
title: "xargs"
description: "xargs, Execute a command with piped arguments coming from another command, a file, etc."
categories: "common"
---
> The input is treated as a single block of text and split into separate pieces on spaces, tabs, newlines and end-of-file.

> More information: <https://pubs.opengroup.org/onlinepubs/9699919799/utilities/xargs.html>.

- Run a command using the input data as arguments:

```bash
arguments_source | xargs command
```

- Run multiple chained commands on the input data:

```bash
arguments_source | xargs sh -c "command1 && command2 | command3"
```

- Delete all files with a `.backup` extension (`-print0` uses a null character to split file names, and `-0` uses it as delimiter):

```bash
find . -name '*.backup' -print0 | xargs -0 rm -v
```

- Execute the command once for each input line, replacing any occurrences of the placeholder (here marked as `_`) with the input line:

```bash
arguments_source | xargs -I _ command _ optional_extra_arguments
```

- Parallel runs of up to `max-procs` processes at a time; the default is 1. If `max-procs` is 0, xargs will run as many processes as possible at a time:

```bash
arguments_source | xargs -P max-procs command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | common/x*: add more information link (#6664) | 2021-10-04T14:32:27 | [99a72c556f56](https://github.com/tldr-pages/tldr/commit/99a72c556f563a928a10ff2c2146ad42d9af2990)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | xargs: add example for multiple commands (#3281) Co-authored-by: Marco Bonelli <mebeim@users.noreply.github.com> | 2019-12-24T20:58:08 | [ba08862d1cbe](https://github.com/tldr-pages/tldr/commit/ba08862d1cbefe934a5fb59a253bafe0934a0891)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: remove superfluous white spaces (#2801) | 2019-02-24T16:47:41 | [ad3772d8cbd5](https://github.com/tldr-pages/tldr/commit/ad3772d8cbd5a61fecfb38ab13bdc7b104b4ecdf)
[Florian Leitner](mailto:fnl@users.noreply.github.com) | xargs: added parallel proc flag -P (#2761) | 2019-02-09T14:09:48 | [3c4d0d0ab159](https://github.com/tldr-pages/tldr/commit/3c4d0d0ab159bcc05bcde1f691e104470e8b09f3)
[okaymaged](mailto:3887838+okaymaged@users.noreply.github.com) | xargs: Show delimiter flag usage (#2111) | 2018-05-18T22:22:49 | [4e75d18be228](https://github.com/tldr-pages/tldr/commit/4e75d18be2288b285ca87d3c6cae6fdeaaf0db39)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | adding tokens around *.backup | 2017-12-10T14:25:58 | [5c45c602a204](https://github.com/tldr-pages/tldr/commit/5c45c602a204ff6568226869f036ba09f8291e5f)
[Sahil Bajaj](mailto:spinningarrow@users.noreply.github.com) | Remove unnecessary braces | 2017-12-10T08:43:26 | [17927812a78b](https://github.com/tldr-pages/tldr/commit/17927812a78b5ace1e27680f229b5c6533344e39)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | xargs: rework page to make it more beginner-friendly (#1039) * xargs: update as agreed on code review. | 2016-10-18T00:02:05 | [262b77aaea2e](https://github.com/tldr-pages/tldr/commit/262b77aaea2ebce16bfbe4295ddfe7189b881212)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | xargs: move specific example, per discussion in #891 | 2016-05-16T14:47:00 | [5667133d6a39](https://github.com/tldr-pages/tldr/commit/5667133d6a3955a788231091e0cd2bc57ede8ed7)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | xargs: add example as discussed in #878 Also moved the concrete example to the end. | 2016-05-16T08:51:34 | [f26d5164ae43](https://github.com/tldr-pages/tldr/commit/f26d5164ae43ab5c03c1e8b82d2553be6f1cb170)
[Andrei Cioara](mailto:andrei@cioara.me) | shortened xargs (#878) rest_of_arguments was misleading | 2016-05-16T08:47:07 | [eb1f864263ba](https://github.com/tldr-pages/tldr/commit/eb1f864263baf2dfc9d8267860b70a1a0e29d8e5)
[Leandro Ostera](mailto:leandro@ostera.io) | Fixes formatting. Man the commit hooks is definitely not working on any of muy computers. Need to revisit why. | 2016-02-16T08:27:16 | [91a1ed798ef5](https://github.com/tldr-pages/tldr/commit/91a1ed798ef53fb77c32d0ef7f9cfe7ad8a87826)
[Leandro Ostera](mailto:leandro@ostera.io) | Fix up formatting and merge conflicts | 2016-02-16T08:16:25 | [e1ea11d1ef4d](https://github.com/tldr-pages/tldr/commit/e1ea11d1ef4d0958b527c2cda74449ebe5eb5a55)
[TiredSounds](mailto:tiredsounds17@gmail.com) | Include path in find example in xargs page. | 2016-02-05T21:48:05 | [c0c114e03300](https://github.com/tldr-pages/tldr/commit/c0c114e03300124f9cc62bf1bec4f4c4ffa87623)
[TiredSounds](mailto:tiredsounds17@gmail.com) | Change 'ls' example for xargs page to 'find -name' | 2016-02-04T22:59:35 | [0419ff65ec22](https://github.com/tldr-pages/tldr/commit/0419ff65ec225c6e05591d93c5b9782c32574113)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | xargs: lint, remove controversial example | 2016-01-29T14:30:51 | [f708f359eb11](https://github.com/tldr-pages/tldr/commit/f708f359eb113b3b8c89045cc99b4a29d3f950b4)
[Alex Flores](mailto:eflores@mdsol.com) | replace example with an OS agnostic example | 2016-01-29T14:30:51 | [85da9a1c0355](https://github.com/tldr-pages/tldr/commit/85da9a1c03551b9a7f97ee1ef67f8630ee37688b)
[Alex Flores](mailto:eflores@mdsol.com) | adds commands to xargs and moves to pages/common - xargs is also native to OS X | 2016-01-29T14:30:51 | [b1d38625d5e6](https://github.com/tldr-pages/tldr/commit/b1d38625d5e65e85a7137f8500313faf47d210c5)


---
author: ['Waldir Pimenta', 'lbonanomi', 'Lucas Gabriel Schneider', 'Marco Bonelli', 'marchersimon']
date: 1618869951
title: "envsubst"
description: "envsubst, Substitutes environment variables with their value in shell format strings."
categories: "common"
---
> Variables to be replaced should be in either `${var}` or `$var` format.

> More information: <https://www.gnu.org/software/gettext/manual/html_node/envsubst-Invocation.html>.

- Replace environment variables in stdin and output to stdout:

```bash
echo '$HOME' | envsubst
```

- Replace environment variables in an input file and output to stdout:

```bash
envsubst < path/to/input_file
```

- Replace environment variables in an input file and output to a file:

```bash
envsubst < path/to/input_file > path/to/output_file
```

- Replace environment variables in an input file from a space-separated list:

```bash
envsubst '$USER $SHELL $HOME' < path/to/input_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | envsubst: clarify examples and description (#3221) | 2019-08-07T07:32:59 | [c2069382350e](https://github.com/tldr-pages/tldr/commit/c2069382350e79ce56d2271a9528a53b2067fdcc)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[lbonanomi](mailto:5369016+lbonanomi@users.noreply.github.com) | envsubst: move to common/ | 2019-05-23T18:15:31 | [36eae03328f8](https://github.com/tldr-pages/tldr/commit/36eae03328f829bf2fdd3cd2c6b8d7ccec857177)


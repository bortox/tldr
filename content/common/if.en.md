---
author: ['Kyle', 'Emily Grace Seville', 'Ruben Vereecken', 'Eric Nielsen', 'Denis Sokolov', 'Alexander Berezovsky', 'bl-ue']
date: 1640493057
title: "if, TLDR Pages"
description: "if, Performs conditional processing in shell scripts."
categories: "common"
---
> See also: `test`, `[`.

> More information: <https://www.gnu.org/software/bash/manual/bash.html#Conditional-Constructs>.

- Execute the specified commands if the condition command's exit status is zero:

```bash
if condition_command; then echo "Condition is true"; fi
```

- Execute the specified commands if the condition command's exit status is not zero:

```bash
if ! condition_command; then echo "Condition is true"; fi
```

- Execute the first specified commands if the condition command's exit status is zero otherwise execute the second specified commands:

```bash
if condition_command; then echo "Condition is true"; else echo "Condition is false"; fi
```

- Check whether a [f]ile exists:

```bash
if [[ -f path/to/file ]]; then echo "Condition is true"; fi
```

- Check whether a [d]irectory exists:

```bash
if [[ -d path/to/directory ]]; then echo "Condition is true"; fi
```

- Check whether a file or directory [e]xists:

```bash
if [[ -e path/to/file_or_directory ]]; then echo "Condition is true"; fi
```

- Check whether a variable is defined:

```bash
if [[ -n "$variable" ]]; then echo "Condition is true"; fi
```

- List all possible conditions (`test` is an alias to `[`; both are commonly used with `if`):

```bash
man [
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | if: update page (#7481) | 2021-12-26T05:30:57 | [018d7f57fbba](https://github.com/tldr-pages/tldr/commit/018d7f57fbba7470baedd4cfdd6cfb685ce3354a)
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | if: modernize (#5351) | 2021-03-08T21:06:24 | [672a67a2db7b](https://github.com/tldr-pages/tldr/commit/672a67a2db7be98a6d822334d73b90a13f20cf05)
[Eric Nielsen](mailto:eric@amalgamar.com.br) | if: actually use if to test a command's success (#5344) Using `{{command}} && {{command1}} -- {{command2}}` does not actually work [...] | 2021-03-04T16:16:42 | [b96c886c4fd7](https://github.com/tldr-pages/tldr/commit/b96c886c4fd7ce8d58d049da39ffb63e7ce7b927)
[Alexander Berezovsky](mailto:a-b@users.noreply.github.com) | if: add if conditions with examples (#3206) | 2019-08-18T19:05:41 | [89a3e79198d9](https://github.com/tldr-pages/tldr/commit/89a3e79198d918dcb431f1bdde7f4442c8941ecc)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Reformatted pages once more | 2016-01-13T12:04:46 | [967633411984](https://github.com/tldr-pages/tldr/commit/9676334119847078e5e05fec393a3fe36991dbc2)
[Denis Sokolov](mailto:denis@sokolov.cc) | for/if/while: add | 2016-01-07T16:40:49 | [27cc01819f77](https://github.com/tldr-pages/tldr/commit/27cc01819f7703b54ddf368990b96ea105d1e18a)


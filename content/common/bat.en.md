---
author: ['Jeremy Nicklas', 'Muhammad Falak R Wani', 'Seth Falco', 'Agustín Covarrubias']
date: 1629050349
title: "bat"
description: "bat, Print and concatenate files."
categories: "common"
---
> A `cat` clone with syntax highlighting and Git integration.

> More information: <https://github.com/sharkdp/bat>.

- Print the contents of a file to the standard output:

```bash
bat file
```

- Concatenate several files into the target file:

```bash
bat file1 file2 > target_file
```

- Append several files into the target file:

```bash
bat file1 file2 >> target_file
```

- Number all output lines:

```bash
bat -n file
```

- Syntax highlight a JSON file:

```bash
bat --language json file.json
```

- Display all supported languages:

```bash
bat --list-languages
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Agustín Covarrubias](mailto:agucova@gmail.com) | bat: add more information link (#4785) * bat: add Spanish translation * bat: add suggestions Co-authored-by: Axel Navarro [...] | 2020-10-24T14:45:49 | [51c0dd2ba4cb](https://github.com/tldr-pages/tldr/commit/51c0dd2ba4cbce05ceed443399619c0f53ab4c31)
[Jeremy Nicklas](mailto:jeremywnicklas@gmail.com) | bat: fix a typo (#2413) | 2018-10-08T04:47:15 | [ac141c5074d0](https://github.com/tldr-pages/tldr/commit/ac141c5074d0a8a937f345d24ffb8c82bd56495f)
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | bat: add page (#2296) (#2297) | 2018-09-06T15:37:32 | [8f0e8546be59](https://github.com/tldr-pages/tldr/commit/8f0e8546be59f8b55b4589fb6145a503ce9d0894)


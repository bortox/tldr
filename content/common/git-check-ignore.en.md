---
author: ['Owen Voke', 'Waldir Pimenta', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1656325392
title: "git check-ignore"
description: "git check-ignore, Analyze and debug Git ignore / exclude ('.gitignore') files."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-check-ignore>.

- Check whether a file or directory is ignored:

```bash
git check-ignore path/to/file_or_directory
```

- Check whether multiple files or directories are ignored:

```bash
git check-ignore path/to/file path/to/directory
```

- Use pathnames, one per line, from stdin:

```bash
git check-ignore --stdin < path/to/file_list
```

- Do not check the index (used to debug why paths were tracked and not ignored):

```bash
git check-ignore --no-index path/to/files_or_directories
```

- Include details about the matching pattern for each path:

```bash
git check-ignore --verbose path/to/files_or_directories
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Owen Voke](mailto:owzie123@gmail.com) | git-check-ignore: add page (#3113) | 2019-06-17T16:51:57 | [5284daaa6433](https://github.com/tldr-pages/tldr/commit/5284daaa6433824e774162fcc0cc140f1c30d9c8)


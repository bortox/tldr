---
author: ['Waldir Pimenta', 'Axel Navarro', 'Seth Falco', 'bl-ue']
date: 1629050349
title: "gh alias, TLDR Pages"
description: "gh alias, Manage GitHub CLI command aliases from the command-line."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_alias>.

- Display the subcommand help:

```bash
gh alias
```

- List all the aliases `gh` is configured to use:

```bash
gh alias list
```

- Create a `gh` subcommand alias:

```bash
gh alias set pv 'pr view'
```

- Set a shell command as a `gh` subcommand:

```bash
gh alias set --shell alias_name command
```

- Delete a command shortcut:

```bash
gh alias delete alias_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | gh-alias: close quoted string (#5156) | 2021-01-17T18:55:43 | [d1b86208a1b7](https://github.com/tldr-pages/tldr/commit/d1b86208a1b7243d796569373f3954d191858225)
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-alias: add page (#5125) * gh-alias: add page * Apply suggestions from code review Co-authored-by: bl-ue <54780737+bl- [...] | 2021-01-10T14:53:18 | [39cc9373a2e9](https://github.com/tldr-pages/tldr/commit/39cc9373a2e9a0e5790145d4dbed4a911512b9ea)


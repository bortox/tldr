---
author: ['Waldir Pimenta', 'Antonio Bustos', 'Reinhart Previano Koentjoro', 'Antoine Amara', 'Aadit Kamat', 'bl-ue', 'marchersimon']
date: 1651488938
title: "gh, TLDR Pages"
description: "gh, Work seamlessly with GitHub from the command-line."
categories: "common"
---
> Some subcommands such as `gh config` have their own usage documentation.

> More information: <https://cli.github.com/>.

- Clone a GitHub repository locally:

```bash
gh repo clone owner/repository
```

- Create a new issue:

```bash
gh issue create
```

- View and filter the open issues of the current repository:

```bash
gh issue list
```

- View an issue in the default web browser:

```bash
gh issue view --web issue_number
```

- Create a pull request:

```bash
gh pr create
```

- View a pull request in the default web browser:

```bash
gh pr view --web pr_number
```

- Check out a specific pull request locally:

```bash
gh pr checkout pr_number
```

- Check the status of a repository's pull requests:

```bash
gh pr status
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | gh*, glab*: standardize documentation (#7957) | 2022-05-02T12:55:38 | [6ed9681dbcd6](https://github.com/tldr-pages/tldr/commit/6ed9681dbcd680e9529c8238221f7fab9cd2c130)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | gh: small wording tweaks for extra clarity (#5157) | 2021-01-17T18:56:17 | [9b64574c3849](https://github.com/tldr-pages/tldr/commit/9b64574c3849e574226d00c6fcf024bd8339cad0)
[Antoine Amara](mailto:amara.antoine@gmail.com) | gh: change command order and fix a mistake on pr/issue view command (#4722) | 2020-10-24T15:46:22 | [60231caf8dd7](https://github.com/tldr-pages/tldr/commit/60231caf8dd77194bf8518a27d685c696c809d81)
[Aadit Kamat](mailto:aadit.k12@gmail.com) | gh: add repo clone example (#4635) | 2020-10-13T12:37:01 | [d3c7c7efad9c](https://github.com/tldr-pages/tldr/commit/d3c7c7efad9cddc4a632dbc063255c696212adf9)
[Antonio Bustos](mailto:antoniobusrod@users.noreply.github.com) | gh: add page (#3854) | 2020-02-17T03:30:39 | [d009c909d269](https://github.com/tldr-pages/tldr/commit/d009c909d26967536430b07fbda8797207efc6aa)


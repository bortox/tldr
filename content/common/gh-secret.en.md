---
author: ['Axel Navarro', 'bl-ue']
date: 1621593705
title: "gh secret"
description: "gh secret, Manage GitHub secrets from the command-line."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_secret>.

- List secret keys for the current repository:

```bash
gh secret list
```

- List secret keys for a specific organization:

```bash
gh secret list --org organization
```

- List secret keys for a specific repository:

```bash
gh secret list --repo owner/repository
```

- Set a secret for the current repository (user will be prompted for the value):

```bash
gh secret set name
```

- Set a secret from a file for the current repository:

```bash
gh secret set name < path/to/file
```

- Set an organization secret for specific repositories:

```bash
gh secret set name --org organization --repos repository1,repository2
```

- Remove a secret for the current repository:

```bash
gh secret remove name
```

- Remove a secret for a specific organization:

```bash
gh secret remove name --org organization
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-secret-set: add page (#5996) | 2021-05-21T12:41:45 | [b0cedebfc189](https://github.com/tldr-pages/tldr/commit/b0cedebfc189328eb94c37f872d05b46ef946007)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-secret: add page (#5133) | 2021-01-16T17:34:13 | [7b68d5cefdb5](https://github.com/tldr-pages/tldr/commit/7b68d5cefdb5736675a98a12e67c3f4f5dd49da6)


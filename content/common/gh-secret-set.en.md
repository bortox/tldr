---
author: ['Axel Navarro']
date: 1621593705
title: "gh secret set"
description: "gh secret set, Create or update GitHub secrets from the command line."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_secret_set>.

- Set a secret for the current repository (user will be prompted for the value):

```bash
gh secret set name
```

- Set a secret from a file for the current repository:

```bash
gh secret set name < path/to/file
```

- Set a secret for a specific repository:

```bash
gh secret set name --body value --repo owner/repository
```

- Set an organization secret for specific repositories:

```bash
gh secret set name --org organization --repos "repository1,repository2,..."
```

- Set an organization secret with a specific visibility:

```bash
gh secret set name --org organization --visibility all|private|selected
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-secret-set: add page (#5996) | 2021-05-21T12:41:45 | [b0cedebfc189](https://github.com/tldr-pages/tldr/commit/b0cedebfc189328eb94c37f872d05b46ef946007)


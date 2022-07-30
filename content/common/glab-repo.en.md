---
author: ['Antoine Amara', 'Reinhart Previano Koentjoro']
date: 1651488938
title: "glab repo"
description: "glab repo, Work with GitLab repositories on the command-line."
categories: "common"
---
> More information: <https://glab.readthedocs.io/en/latest/repo/index.html#synopsis>.

- Create a new repository (if the repository name is not set, the default name will be the name of the current directory):

```bash
glab repo create name
```

- Clone a repository:

```bash
glab repo clone owner/repository
```

- Fork and clone a repository:

```bash
glab repo fork owner/repository --clone
```

- View a repository in the default web browser:

```bash
glab repo view owner/repository --web
```

- Search some repositories in the GitLab instance:

```bash
glab repo search -s search_string
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | gh*, glab*: standardize documentation (#7957) | 2022-05-02T12:55:38 | [6ed9681dbcd6](https://github.com/tldr-pages/tldr/commit/6ed9681dbcd680e9529c8238221f7fab9cd2c130)
[Antoine Amara](mailto:amara.antoine@gmail.com) | glab-repo: add page (#7558) | 2021-12-29T18:50:26 | [53595174126f](https://github.com/tldr-pages/tldr/commit/53595174126f28fe9b9c4fbc4f42e538c93076ce)


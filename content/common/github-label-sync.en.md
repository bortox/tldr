---
author: ['Owen Voke', 'Seth Falco', 'bl-ue', 'Marco Bonelli', 'Axel Navarro']
date: 1656325392
title: "github-label-sync, TLDR Pages"
description: "github-label-sync, A command-line interface for synchronizing GitHub labels."
categories: "common"
---
> More information: <https://github.com/Financial-Times/github-label-sync>.

- Synchronize labels using a local `labels.json` file:

```bash
github-label-sync --access-token token repository_name
```

- Synchronize labels using a specific labels JSON file:

```bash
github-label-sync --access-token token --labels url|path/to/json_file repository_name
```

- Perform a dry run instead of actually synchronizing labels:

```bash
github-label-sync --access-token token --dry-run repository_name
```

- Keep labels that aren't in `labels.json`:

```bash
github-label-sync --access-token token --allow-added-labels repository_name
```

- Synchronize using the `GITHUB_ACCESS_TOKEN` environment variable:

```bash
github-label-sync repository_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[Axel Navarro](mailto:navarroaxel@gmail.com) | github-label-sync: use repo as more information link (#7591) | 2021-12-31T13:21:30 | [5283cc7c42e6](https://github.com/tldr-pages/tldr/commit/5283cc7c42e69b9d816fb49e9b46c7e1860ba373)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | github-label-sync: add page (#2967) | 2019-05-18T10:58:16 | [f3f3e29c954c](https://github.com/tldr-pages/tldr/commit/f3f3e29c954c894612a9337925e1f41dc6a920dd)


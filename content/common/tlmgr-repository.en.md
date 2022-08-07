---
author: ['marchersimon']
date: 1659806044
title: "tlmgr repository"
description: "tlmgr repository, Manage repositories of a TeX Live installation."
categories: "common"
---
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- List all configured repositories and their tags (if set):

```bash
tlmgr repository list
```

- List all packages available in a specific repository:

```bash
tlmgr repository list path|url|tag
```

- Add a new repository with a specific tag (the tag is not required):

```bash
sudo tlmgr repository add path|url tag
```

- Remove a specific repository:

```bash
sudo tlmgr repository remove path|url|tag
```

- Set a new list of repositories, overwriting the previous list:

```bash
sudo tlmgr repository set path|url|tag#tag path|url|tag#tag ...
```

- Show the verification status of all configured repositories:

```bash
tlmgr repository status
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tlmgr-repository: add page (#8289) | 2022-08-06T19:14:04 | [1e83ba1d7ea8](https://github.com/tldr-pages/tldr/commit/1e83ba1d7ea82d193f8447423695a0b0d572db6c)


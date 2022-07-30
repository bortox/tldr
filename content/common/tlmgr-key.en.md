---
author: ['marchersimon']
date: 1657535703
title: "tlmgr key"
description: "tlmgr key, Manage GPG keys used to verify TeX Live databases."
categories: "common"
---
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- List all keys for TeX Live:

```bash
tlmgr key list
```

- Add a key from a specific file:

```bash
sudo tlmgr key add path/to/key.gpg
```

- Add a key from stdin:

```bash
cat path/to/key.gpg | sudo tlmgr key add -
```

- Remove a specific key by its ID:

```bash
sudo tlmgr key remove key_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tlmgr-key: add page (#8193) | 2022-07-11T12:35:03 | [88fd34d9f943](https://github.com/tldr-pages/tldr/commit/88fd34d9f9436f13f2b7ea2e46f01d82c2fe7a26)


---
author: ['Axel Navarro', 'bl-ue']
date: 1621541621
title: "gh ssh-key"
description: "gh ssh-key, Manage GitHub SSH keys from the command-line."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_ssh-key>.

- Display help:

```bash
gh ssh-key
```

- List SSH keys for the currently authenticated user:

```bash
gh ssh-key list
```

- Add an SSH key to the currently authenticated user's account:

```bash
gh ssh-key add path/to/key.pub
```

- Add an SSH key to the currently authenticated user's account with a specific title:

```bash
gh ssh-key add --title title path/to/key.pub
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-ssh-key: add page (#5308) | 2021-02-24T14:39:13 | [e2082f8adce9](https://github.com/tldr-pages/tldr/commit/e2082f8adce9cac4f322c4e5e35f417fce5bf3b6)


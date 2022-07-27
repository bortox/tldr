---
author: ['Seth Falco', 'Starbeamrainbowlabs', 'bl-ue']
date: 1656325392
title: "git lfs, TLDR Pages"
description: "git lfs, Work with large files in Git repositories."
categories: "common"
---
> More information: <https://git-lfs.github.com>.

- Initialize Git LFS:

```bash
git lfs install
```

- Track files that match a glob:

```bash
git lfs track '*.bin'
```

- Change the Git LFS endpoint URL (useful if the LFS server is separate from the Git server):

```bash
git config -f .lfsconfig lfs.url lfs_endpoint_url
```

- List tracked patterns:

```bash
git lfs track
```

- List tracked files that have been committed:

```bash
git lfs ls-files
```

- Push all Git LFS objects to the remote server (useful if errors are encountered):

```bash
git lfs push --all remote_name branch_name
```

- Fetch all Git LFS objects:

```bash
git lfs fetch
```

- Checkout all Git LFS objects:

```bash
git lfs checkout
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git-lfs: add fetch and checkout subcommands (#3884) | 2020-03-06T19:48:14 | [4c831ae0d5a3](https://github.com/tldr-pages/tldr/commit/4c831ae0d5a3e27788404df2bd5684e87d1775ba)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git lfs: add page (#3302) | 2019-10-05T04:06:34 | [0d96f785506b](https://github.com/tldr-pages/tldr/commit/0d96f785506b7b806b4f50cbd5e9729ff74d2e03)


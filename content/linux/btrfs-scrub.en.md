---
author: ['Starbeamrainbowlabs']
date: 1610017578
title: "btrfs scrub"
description: "btrfs scrub, Scrub btrfs filesystems to verify data integrity."
categories: "linux"
---
> It is recommended to run a scrub once a month.

> More information: <https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-scrub>.

- Start a scrub:

```bash
sudo btrfs scrub start path/to/btrfs_mount
```

- Show the status of an ongoing or last completed scrub:

```bash
sudo btrfs scrub status path/to/btrfs_mount
```

- Cancel an ongoing scrub:

```bash
sudo btrfs scrub cancel path/to/btrfs_mount
```

- Resume a previously cancelled scrub:

```bash
sudo btrfs scrub resume path/to/btrfs_mount
```

- Start a scrub, but wait until the scrub finishes before exiting:

```bash
sudo btrfs scrub start -B path/to/btrfs_mount
```

- Start a scrub in quiet mode (does not print errors or statistics):

```bash
sudo btrfs scrub start -q path/to/btrfs_mount
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | btrfs-scrub: add page (#5104) | 2021-01-07T12:06:18 | [11b78886d058](https://github.com/tldr-pages/tldr/commit/11b78886d058a9f8c15e8ee1132b8cfe03fba220)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Oops, I shouldn't have commited to master. | 2021-01-07T03:39:35 | [5d7fabcdfacf](https://github.com/tldr-pages/tldr/commit/5d7fabcdfacf0e915b5ac61cdb5de81d52fa3785)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | btrfs-scrub: add page | 2021-01-07T03:38:33 | [9d62a7d44b83](https://github.com/tldr-pages/tldr/commit/9d62a7d44b83b0bac62afe5abf0e7c8a3a95f448)


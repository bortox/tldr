---
author: ['teeteejo', 'marchersimon']
date: 1618584134
title: "e2freefrag"
description: "e2freefrag, Print the free space fragmentation information for ext2/ext3/ext4 filesystems."
categories: "linux"
---
> More information: <https://manned.org/e2freefrag>.

- Check how many free blocks are present as contiguous and aligned free space:

```bash
e2freefrag /dev/sdXN
```

- Specify chunk size in kilobytes to print how many free chunks are available:

```bash
e2freefrag -c chunk_size_in_kb /dev/sdXN
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[teeteejo](mailto:72230915+teeteejo@users.noreply.github.com) | e2freefrag: add page (#4512) | 2020-10-06T18:12:23 | [290544381ec8](https://github.com/tldr-pages/tldr/commit/290544381ec806d819b20fb8fe5fbb5b5ba659da)


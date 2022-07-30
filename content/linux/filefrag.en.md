---
author: ['teeteejo', 'marchersimon']
date: 1618584134
title: "filefrag"
description: "filefrag, Report how badly fragmented a particular file might be."
categories: "linux"
---
> More information: <https://manned.org/filefrag>.

- Display a report for a specific file:

```bash
filefrag path/to/file
```

- Display a report for space-separated list of files:

```bash
filefrag path/to/file1 path/to/file2
```

- Display a report using a 1024 byte blocksize:

```bash
filefrag -b path/to/file
```

- Sync the file before requesting the mapping:

```bash
filefrag -s path/to/files
```

- Display mapping of extended attributes:

```bash
filefrag -x path/to/files
```

- Display a report with verbose information:

```bash
filefrag -v path/to/files
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[teeteejo](mailto:72230915+teeteejo@users.noreply.github.com) | filefrag: add page (#4487) | 2020-10-05T17:18:47 | [7012ecf00ea0](https://github.com/tldr-pages/tldr/commit/7012ecf00ea0050537910ad355ae671840dcf70e)


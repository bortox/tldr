---
author: ['pixel', 'Seth Falco', 'marchersimon']
date: 1633300301
title: "spectre-meltdown-checker, TLDR Pages"
description: "spectre-meltdown-checker, Spectre and Meltdown mitigation detection tool."
categories: "linux"
---
> More information: <https://manned.org/spectre-meltdown-checker>.

- Check the currently running kernel for Spectre or Meltdown:

```bash
sudo spectre-meltdown-checker
```

- Check the currently running kernel and show an explanation of the actions to take to mitigate a vulnerability:

```bash
sudo spectre-meltdown-checker --explain
```

- Check for specific variants (defaults to all):

```bash
sudo spectre-meltdown-checker --variant 1|2|3|3a|4|l1tf|msbds|mfbds|mlpds|mdsum|taa|mcespc|srbds
```

- Display output using a specific output format:

```bash
sudo spectre-meltdown-checker --batch text|json|nrpe|prometheus|short
```

- Don't use the `/sys` interface even if present:

```bash
sudo spectre-meltdown-checker --no-sysfs
```

- Check a non-running kernel:

```bash
sudo spectre-meltdown-checker --kernel path/to/kernel_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | *: removed .1 at the end of manned.org links where it was unnecessary (#6752) | 2021-10-04T00:31:41 | [ceb6654610e9](https://github.com/tldr-pages/tldr/commit/ceb6654610e9bf343485e918edfc5a90691b89d1)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | spectre-meltdown-checker: add page (#5670) | 2021-04-02T21:56:51 | [9e99f04b9895](https://github.com/tldr-pages/tldr/commit/9e99f04b9895e157ee77520024cd1b77f015d66e)


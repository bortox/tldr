---
author: ['Muhammad Falak R Wani']
date: 1636198048
title: "rpmspec"
description: "rpmspec, Query a RPM spec file."
categories: "linux"
---
> More information: <https://manned.org/rpmspec>.

- List binary packages which would be generated from a rpm spec file:

```bash
rpmspec --query path/to/rpm.spec
```

- List all options for `--queryformat`:

```bash
rpmspec --querytags
```

- Get summary information for single binary packages generated from a rpm spec file:

```bash
rpmspec --query --queryformat "%{name}: %{summary}\n" path/to/rpm.spec
```

- Get the source package which would be generated from a rpm spec file:

```bash
rpmspec --query --srpm path/to/rpm.spec
```

- Parse a rpm spec file to `stdout`:

```bash
rpmspec --parse path/to/rpm.spec
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | rpmspec: add --querytags example (#7209) | 2021-11-06T12:27:28 | [06cddcfcbe5c](https://github.com/tldr-pages/tldr/commit/06cddcfcbe5cf410aefc496c37cadb98480b4591)
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | rpmspec: add page (#6779) Signed-off-by: Muhammad Falak R Wani <falakreyaz@gmail.com> Co-authored-by: Axel Navarro [...] | 2021-10-06T15:30:00 | [371d2c899723](https://github.com/tldr-pages/tldr/commit/371d2c89972350da4b62acfeed89d7daebcd1afb)


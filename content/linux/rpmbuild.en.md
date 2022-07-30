---
author: ['hellojukay']
date: 1604175605
title: "rpmbuild"
description: "rpmbuild, RPM Package Build tool."
categories: "linux"
---
> More information: <https://docs.fedoraproject.org/en-US/quick-docs/creating-rpm-packages/>.

- Build binary and source packages:

```bash
rpmbuild -ba path/to/spec_file
```

- Build a binary package without source package:

```bash
rpmbuild -bb path/to/spec_file
```

- Specify additional variables when building a package:

```bash
rpmbuild -bb path/to/spec_file --define "variable1 value1" --define "variable2 value2"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[hellojukay](mailto:hellojukay@163.com) | rpmbuild: add page (#4864) | 2020-10-31T21:20:05 | [4a7fc6ceb11d](https://github.com/tldr-pages/tldr/commit/4a7fc6ceb11d3f957a7ad854def67779ba450bc5)


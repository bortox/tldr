---
author: ['marchersimon', 'Peter Tripp', 'BillLucky']
date: 1629745639
title: "jmap"
description: "jmap, Java Memory Map Tool."
categories: "common"
---
> More information: <https://docs.oracle.com/javase/7/docs/technotes/tools/share/jmap.html>.

- Print shared object mappings for a Java process (output like pmap):

```bash
jmap java_pid
```

- Print heap summary information:

```bash
jmap -heap filename.jar java_pid
```

- Print histogram of heap usage by type:

```bash
jmap -histo java_pid
```

- Dump contents of the heap into a binary file for analysis with jhat:

```bash
jmap -dump:format=b,file=filename java_pid
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[BillLucky](mailto:bill.libiao@gmail.com) | jmap: add more information link (#6404) | 2021-08-23T21:07:19 | [b7bc62dfbbfb](https://github.com/tldr-pages/tldr/commit/b7bc62dfbbfbe6c5a6ed86842d17c0d474b6c90e)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace `java` with `Java` and `c++` with `C++` (#6224) | 2021-07-13T10:59:48 | [b615ea1e3495](https://github.com/tldr-pages/tldr/commit/b615ea1e34951c855e72470b73522ed0e0963d87)
[Peter Tripp](mailto:peter@chartio.com) | Copy pasta oopsies. | 2016-02-16T21:36:36 | [99396717c471](https://github.com/tldr-pages/tldr/commit/99396717c4716f8592a012f0f03cac2ab1d3d91e)
[Peter Tripp](mailto:peter@chartio.com) | Java debug tools. Jstack, jmap and jhat. | 2016-02-16T20:27:52 | [67e2c723aff4](https://github.com/tldr-pages/tldr/commit/67e2c723aff4502501e0ac567ac5364348f6f3d7)


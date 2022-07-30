---
author: ['marchersimon', 'Peter Tripp', 'lincc']
date: 1632006650
title: "jstack"
description: "jstack, Java Stack Trace Tool."
categories: "common"
---
> More information: <https://manned.org/jstack>.

- Print Java stack traces for all threads in a Java process:

```bash
jstack java_pid
```

- Print mixed mode (Java/C++) stack traces for all threads in a Java process:

```bash
jstack -m java_pid
```

- Print stack traces from Java core dump:

```bash
jstack /usr/bin/java file.core
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | jobs, jstack, kill, killall: add more information link (#6545) | 2021-09-19T01:10:50 | [0e7393b78f1d](https://github.com/tldr-pages/tldr/commit/0e7393b78f1db36b5dfb377b3062c6b551a69e58)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace `java` with `Java` and `c++` with `C++` (#6224) | 2021-07-13T10:59:48 | [b615ea1e3495](https://github.com/tldr-pages/tldr/commit/b615ea1e34951c855e72470b73522ed0e0963d87)
[Peter Tripp](mailto:peter@chartio.com) | Copy pasta oopsies. | 2016-02-16T21:36:36 | [99396717c471](https://github.com/tldr-pages/tldr/commit/99396717c4716f8592a012f0f03cac2ab1d3d91e)
[Peter Tripp](mailto:peter@chartio.com) | Java debug tools. Jstack, jmap and jhat. | 2016-02-16T20:27:52 | [67e2c723aff4](https://github.com/tldr-pages/tldr/commit/67e2c723aff4502501e0ac567ac5364348f6f3d7)


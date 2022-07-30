---
author: ['Karthikeyan Vaithilingam', 'bl-ue', 'marchersimon']
date: 1626166788
title: "jenv"
description: "jenv, Command-line tool to manage the 'JAVA_HOME' environment variable."
categories: "common"
---
> More information: <https://www.jenv.be/>.

- Add a Java version to jEnv:

```bash
jenv add path/to/jdk_home
```

- Display the current JDK version used:

```bash
jenv version
```

- Display all managed JDKs:

```bash
jenv versions
```

- Set the global JDK version:

```bash
jenv global java_version
```

- Set the JDK version for the current shell session:

```bash
jenv shell java_version
```

- Enable a jEnv plugin:

```bash
jenv enable-plugin plugin_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace `java` with `Java` and `c++` with `C++` (#6224) | 2021-07-13T10:59:48 | [b615ea1e3495](https://github.com/tldr-pages/tldr/commit/b615ea1e34951c855e72470b73522ed0e0963d87)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | jenv: add page (#4529) | 2020-10-07T22:06:04 | [734462967d39](https://github.com/tldr-pages/tldr/commit/734462967d395a1936979164b9ad8b970e489fa1)


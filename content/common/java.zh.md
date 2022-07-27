---
author: ['Alan Chang', 'marchersimon', 'bl-ue', 'lincc']
date: 1643487459
title: "java, TLDR Pages"
description: "java, Java 程序启动器。"
categories: "common"
---
> 更多信息：<https://docs.oracle.com/en/java/javase/17/docs/specs/man/java.html>.

- 通过提供类名称运行一个含有 main 函数的 java .class 程序：

```bash
java 类名称
```

- 运行一个 .jar 程序：

```bash
java -jar 文件名.jar
```

- 运行一个 .jar 程序并且在端口 5005 等待调试器：

```bash
java -agentlib:jdwp=transport=dt_socket,server=y,suspend=y,address=*:5005 -jar 文件名.jar
```

- 显示 JDK, JRE 和 HotSpot 的版本：

```bash
java -version
```

- 显示详细的帮助：

```bash
java -help
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Alan Chang](mailto:tcode2k16@users.noreply.github.com) | java: add Chinese translation (#4573) | 2020-10-09T01:35:50 | [5eccb4101cd0](https://github.com/tldr-pages/tldr/commit/5eccb4101cd06aa7d0fa01f4a007dd56fce2dd28)


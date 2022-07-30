---
author: ['Alan Chang', 'bl-ue', 'Lucas Gabriel Schneider', 'lincc']
date: 1631818200
title: "javac"
description: "javac, Java 程序编译器。"
categories: "common"
---
> 更多信息：<https://docs.oracle.com/en/java/javase/17/docs/specs/man/javac.html>.

- 编译一个 `.java` 文件：

```bash
javac 文件名.java
```

- 编译多个 `.java` 文件：

```bash
javac 文件名1.java 文件名2.java 文件名3.java
```

- 编译当前目录内所有 `.java` 文件：

```bash
javac *.java
```

- 编译一个 `.java` 文件并将生成的 class 字节码文件放入一个指定目录：

```bash
javac -d 输出目录 文件名.java
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | exec, javac: add more information link (#6536) | 2021-09-16T20:50:00 | [53bb0828896b](https://github.com/tldr-pages/tldr/commit/53bb0828896bfcca7b5ce118fe241ef20c7a6fb0)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Alan Chang](mailto:tcode2k16@users.noreply.github.com) | javac: add Chinese translation (#4577) | 2020-10-09T17:19:37 | [2970e687f1db](https://github.com/tldr-pages/tldr/commit/2970e687f1db6c1c408453cc8f03d207e5a37ff5)


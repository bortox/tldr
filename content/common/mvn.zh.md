---
author: ['Nicolas Kosinski', 'BillLucky', 'bl-ue', 'marchersimon']
date: 1633112881
title: "mvn, TLDR Pages"
description: "mvn, Apache Maven."
categories: "common"
---
> 用于构建和管理基于 Java 的项目的工具。

> 更多信息：<https://maven.apache.org>.

- 编译项目：

```bash
mvn compile
```

- 将编译后的代码打包成可分发格式，比如 `jar`：

```bash
mvn package
```

- 编译和打包，跳过单元测试：

```bash
mvn package -DskipTests
```

- 在本地 maven 存储库中安装构建的包（这也会调用 compile 和 package 命令）：

```bash
mvn install
```

- 从目标目录中删除构建工件，通常用来清理之前的编译结果：

```bash
mvn clean
```

- 执行清理操作，然后进行编译打包：

```bash
mvn clean package
```

- 执行清理操作并使用给定的构建配置打包代码，比如 `profileId` 如果有 dev、test、pro，可以指定其中一个 `profileId` 用来选择具体执行环境：

```bash
mvn clean -PprofileId package
```

- 使用 main 方法运行一个类：

```bash
mvn exec:java -Dexec.mainClass="com.example.Main" -Dexec.args="参数1 参数2"
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Nicolas Kosinski](mailto:nicokosi@users.noreply.github.com) | mvn: simplify skip unit tests (#6448) | 2021-09-01T18:39:12 | [449267ef131c](https://github.com/tldr-pages/tldr/commit/449267ef131c2d8c5269b5903682c5c4ef98ddf7)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[BillLucky](mailto:bill.libiao@gmail.com) | mvn: add Chinese translation (#6080) | 2021-05-31T13:52:43 | [5003d6a97f13](https://github.com/tldr-pages/tldr/commit/5003d6a97f1308d9bf173c4133c249992eac570e)


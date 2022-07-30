---
author: ['Agniva De Sarker', 'jdvega', 'Nicolas Kosinski', 'Juan D. Vega', 'pxgamer', 'Marco Bonelli']
date: 1630514352
title: "mvn"
description: "mvn, Apache Maven."
categories: "common"
---
> Tool for building and managing Java-based projects.

> More information: <https://maven.apache.org>.

- Compile a project:

```bash
mvn compile
```

- Compile and package the compiled code in its distributable format, such as a `jar`:

```bash
mvn package
```

- Compile and package, skipping unit tests:

```bash
mvn package -DskipTests
```

- Install the built package in local maven repository. (This will invoke the compile and package commands too):

```bash
mvn install
```

- Delete build artifacts from the target directory:

```bash
mvn clean
```

- Do a clean and then invoke the package phase:

```bash
mvn clean package
```

- Clean and then package the code with a given build profile:

```bash
mvn clean -Pprofile package
```

- Run a class with a main method:

```bash
mvn exec:java -Dexec.mainClass="com.example.Main" -Dexec.args="arg1 arg2"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@users.noreply.github.com) | mvn: simplify skip unit tests (#6448) | 2021-09-01T18:39:12 | [449267ef131c](https://github.com/tldr-pages/tldr/commit/449267ef131c2d8c5269b5903682c5c4ef98ddf7)
[pxgamer](mailto:owzie123@gmail.com) | mvn: add link to homepage | 2019-06-04T21:29:40 | [21ca990661e8](https://github.com/tldr-pages/tldr/commit/21ca990661e8ef071cad208a52c8d14c84306a46)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Restructuring the entire page | 2017-12-13T07:13:18 | [524b30871267](https://github.com/tldr-pages/tldr/commit/524b30871267cdc44eb290ab850ca505af28112e)
[jdvega](mailto:jdvega@idealista.com) | change example, change order and inprove descriptions | 2017-12-12T15:21:07 | [9daf498da909](https://github.com/tldr-pages/tldr/commit/9daf498da909ee6fe09e4cbe5a9e9cfd62e25569)
[Juan D. Vega](mailto:jdvr@users.noreply.github.com) | Update mvn.md | 2017-12-01T12:00:44 | [ea10d748b06c](https://github.com/tldr-pages/tldr/commit/ea10d748b06caad89c2120120e9308cf4654175f)
[Juan D. Vega](mailto:jdvr@users.noreply.github.com) | Update mvn.md | 2017-11-29T14:08:23 | [4e4c632820c0](https://github.com/tldr-pages/tldr/commit/4e4c632820c005ca439d713a44368df6e96fe115)
[Juan D. Vega](mailto:jdvr@users.noreply.github.com) | Update mvn.md | 2017-11-29T09:42:02 | [cb9dd064e167](https://github.com/tldr-pages/tldr/commit/cb9dd064e1677ebc035c6bb49fdf7f89a3ad5c55)
[Juan D. Vega](mailto:jdvr@users.noreply.github.com) | Create mvn.md | 2017-11-29T09:35:48 | [99d109399a11](https://github.com/tldr-pages/tldr/commit/99d109399a11ce817ef6c918edd84d1230901ad6)


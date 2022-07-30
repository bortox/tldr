---
author: ['Qtrain', 'J053Fabi0', 'Erik Weibust', 'Lucas Gabriel Schneider', 'pxgamer', 'Max Rydahl Andersen', 'Ruben Vereecken']
date: 1635787532
title: "java"
description: "java, Java Application Launcher."
categories: "common"
---
> More information: <https://docs.oracle.com/en/java/javase/17/docs/specs/man/java.html>.

- Execute a java `.class` file that contains a main method by using just the class name:

```bash
java classname
```

- Execute a java program and use additional third-party or user-defined classes:

```bash
java -classpath path/to/classes1:path/to/classes2:. classname
```

- Execute a `.jar` program:

```bash
java -jar filename.jar
```

- Execute a `.jar` program with debug waiting to connect on port 5005:

```bash
java -agentlib:jdwp=transport=dt_socket,server=y,suspend=y,address=*:5005 -jar filename.jar
```

- Display JDK, JRE and HotSpot versions:

```bash
java -version
```

- Display usage information for the java command:

```bash
java -help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Erik Weibust](mailto:erik@weibust.net) | java: add classpath example and update link (#7358) | 2021-11-01T18:25:32 | [057a5c52fabe](https://github.com/tldr-pages/tldr/commit/057a5c52fabe67213f1e3490d1fb80ccfd76fdfc)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Max Rydahl Andersen](mailto:max.andersen@gmail.com) | java: add debug info (#4266) | 2020-09-17T13:02:16 | [4ac62cbe9cde](https://github.com/tldr-pages/tldr/commit/4ac62cbe9cde3e2055b022a8e27d50a6c9020b4e)
[Erik Weibust](mailto:erik@weibust.net) | java: added help argument (#3375) | 2019-10-11T21:03:27 | [df29c21ec913](https://github.com/tldr-pages/tldr/commit/df29c21ec91382bc0790aa2f00a018ed8b3e1ae0)
[pxgamer](mailto:owzie123@gmail.com) | java: add link to homepage | 2019-06-06T04:42:48 | [b0f35ddc5faa](https://github.com/tldr-pages/tldr/commit/b0f35ddc5faa3d659352f6e46f8bb77f145f13bc)
[J053Fabi0](mailto:arguellojf1@gmail.com) | idk how to name this one xD | 2017-12-31T07:45:50 | [da8ac599a12d](https://github.com/tldr-pages/tldr/commit/da8ac599a12d2a158141b94d7b47b84483afcbe4)
[J053Fabi0](mailto:arguellojf1@gmail.com) | I just hope isn't too much | 2017-12-31T05:37:37 | [290b6268a6ee](https://github.com/tldr-pages/tldr/commit/290b6268a6ee9a24b95438e093f45f5a66a3559b)
[J053Fabi0](mailto:arguellojf1@gmail.com) | end in a colon and surrounded by empty lines | 2017-12-30T19:38:44 | [2b2a1a5e5a43](https://github.com/tldr-pages/tldr/commit/2b2a1a5e5a435504f4260798f886d6c6dc2513df)
[J053Fabi0](mailto:arguellojf1@gmail.com) | <java>: page edit; add command Custom input and output when compiling a class with the java command | 2017-12-30T19:32:10 | [b172d976671c](https://github.com/tldr-pages/tldr/commit/b172d976671c212f61a9cb054143487253b9bd0a)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Qtrain](mailto:michaelquatrani@gmail.com) | java command | 2015-12-16T21:41:36 | [df6c9dc3080f](https://github.com/tldr-pages/tldr/commit/df6c9dc3080f900dd438af77e5cecdc7f47eeb56)


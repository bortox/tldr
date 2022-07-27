---
author: ['Robbie S', 'Eric Chang', 'Ruben Vereecken', 'Lucas Gabriel Schneider', 'lincc', 'Muhammad-Sharif Moustafa']
date: 1631818200
title: "javac, TLDR Pages"
description: "javac, Java Application Compiler."
categories: "common"
---
> More information: <https://docs.oracle.com/en/java/javase/17/docs/specs/man/javac.html>.

- Compile a `.java` file:

```bash
javac file.java
```

- Compile several `.java` files:

```bash
javac file1.java file2.java file3.java
```

- Compile all `.java` files in current directory:

```bash
javac *.java
```

- Compile a `.java` file and place the resulting class file in a specific directory:

```bash
javac -d path/to/some/directory file.java
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | exec, javac: add more information link (#6536) | 2021-09-16T20:50:00 | [53bb0828896b](https://github.com/tldr-pages/tldr/commit/53bb0828896bfcca7b5ce118fe241ef20c7a6fb0)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Eric Chang](mailto:ericchang2017@u.northwestern.edu) | javac: use 'file' instead of 'filename' (#1945) | 2018-01-28T12:09:13 | [e61d6a6ef740](https://github.com/tldr-pages/tldr/commit/e61d6a6ef7406930f78a8ba7ba9d9a3e93bf9cec)
[Muhammad-Sharif Moustafa](mailto:mshmoustafa@gmail.com) | javac: add -d and multiple files examples | 2016-01-27T06:23:26 | [5bbfd2601d49](https://github.com/tldr-pages/tldr/commit/5bbfd2601d49c54b2c995c59fd1d80d37f37d9f0)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Robbie S](mailto:robbie@selwynsoftware.com) | Added javac to common | 2015-12-29T03:11:07 | [1a71ade49c67](https://github.com/tldr-pages/tldr/commit/1a71ade49c67e4eca8a0df4c33a9b94bde4e56da)


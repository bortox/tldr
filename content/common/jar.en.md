---
author: ['Artur Skowronski', 'Raghu Kalluri', 'pxgamer', 'Eran Harel']
date: 1580849795
title: "jar"
description: "jar, Java Applications/Libraries Packager."
categories: "common"
---
> More information: <https://docs.oracle.com/javase/tutorial/deployment/jar/basicsindex.html>.

- Recursively archive all files in the current directory into a .jar file:

```bash
jar cf file.jar *
```

- Unzip .jar/.war file to the current directory:

```bash
jar -xvf file.jar
```

- List a .jar/.war file content:

```bash
jar tf path/to/file.jar
```

- List a .jar/.war file content with verbose output:

```bash
jar tvf path/to/file.jar
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Raghu Kalluri](mailto:raghu1kalluri@gmail.com) | jar: Added 'cf' example (#3827) | 2020-02-04T21:56:35 | [7e8b6b3eb8cf](https://github.com/tldr-pages/tldr/commit/7e8b6b3eb8cfabc932c864683480c0d8993a132f)
[pxgamer](mailto:owzie123@gmail.com) | jar: add link to homepage | 2019-06-06T04:42:48 | [5ad1d58e2e3c](https://github.com/tldr-pages/tldr/commit/5ad1d58e2e3c2a3634dbb567add6ce4224126c12)
[Eran Harel](mailto:harel.eran@gmail.com) | jar: add jar listing options examples (#2299) | 2018-09-06T13:51:52 | [bab953281a9a](https://github.com/tldr-pages/tldr/commit/bab953281a9a66ae62b9c7fdea6e8529cd6835e8)
[Artur Skowronski](mailto:articles.pl@gmail.com) | Create jar with handy info about usage of jar | 2016-01-15T16:45:17 | [c6288e06c803](https://github.com/tldr-pages/tldr/commit/c6288e06c8030e1e764a1dea15244680b7860b52)


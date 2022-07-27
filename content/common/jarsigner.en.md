---
author: ['Pierre Rudloff']
date: 1573593620
title: "jarsigner, TLDR Pages"
description: "jarsigner, Sign and verify Java Archive (JAR) files."
categories: "common"
---
> More information: <https://docs.oracle.com/javase/9/tools/jarsigner.htm>.

- Sign a JAR file:

```bash
jarsigner path/to/file.jar keystore_alias
```

- Sign a JAR file with a specific algorithm:

```bash
jarsigner -sigalg algorithm path/to/file.jar keystore_alias
```

- Verify the signature of a JAR file:

```bash
jarsigner -verify path/to/file.jar
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | jarsigner: add page (#3547) | 2019-11-12T22:20:20 | [262f56eed392](https://github.com/tldr-pages/tldr/commit/262f56eed3920c22d5845773207a03155232c669)


---
author: ['Lucas Gabriel Schneider', 'Levi Rizki Saputra', 'lincc']
date: 1643487459
title: "java, TLDR Pages"
description: "java, Peluncur Aplikasi Java."
categories: "common"
---
> Informasi lebih lanjut: <https://docs.oracle.com/en/java/javase/17/docs/specs/man/java.html>.

- Menjalankan berkas java `.class` yang mengandung method main dengan hanya menggunakan nama class:

```bash
java nama_class
```

- Menjalankan program `.jar`:

```bash
java -jar nama_berkas.jar
```

- Menjalankan program `.jar` dengan menunggu debugger terhubung ke port 5005:

```bash
java -agentlib:jdwp=transport=dt_socket,server=y,suspend=y,address=*:5005 -jar nama_berkas.jar
```

- Menampilkan versi JDK, JRE dan HotSpot:

```bash
java -version
```

- Menampilkan informasi penggunaan untuk perintah java:

```bash
java -help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Levi Rizki Saputra](mailto:42236775+levirs565@users.noreply.github.com) | hugo, java, ls, mongod, pip, pip3, rm: add Indonesian translation (#4911) | 2020-11-01T15:37:12 | [3babbbc15b09](https://github.com/tldr-pages/tldr/commit/3babbbc15b093e75bde8b6f066af047dc0957f98)


---
author: ['Zein Haddad']
date: 1645877071
title: "gcc"
description: "gcc, Praproses dan kompilasi kode sumber C dan C++, lalu rakit dan gabungkan bersama-sama."
categories: "common"
---
> Informasi lebih lanjut: <https://gcc.gnu.org>.

- Mengubah beberapa sumber kode menjadi program:

```bash
gcc sumber1.c sumber2.c --output program
```

- Mengizinkan peringatan dan simbol debug di output:

```bash
gcc sumber.c -Wall -Og --output program
```

- Menyertakan pustaka dari direktori yang berbeda:

```bash
gcc sumber.c --output program -Ijalur_header -Ljalur_pustaka -lnama_pustaka
```

- Mengkompilasi kode sumber ke dalam bahasa tingkat rendah (assembly):

```bash
gcc -S sumber.c
```

- Mengkompilasi kode sumber tanpa digabungkan:

```bash
gcc -c sumber.c
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Zein Haddad](mailto:zeinhaddad02@gmail.com) | gcc, g++: add Indonesian translation (#7808) | 2022-02-26T13:04:31 | [50b176125838](https://github.com/tldr-pages/tldr/commit/50b176125838055f5862216fb1bb3fe11cdf3e11)


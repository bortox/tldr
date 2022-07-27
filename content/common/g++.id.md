---
author: ['Zein Haddad']
date: 1645877071
title: "g++, TLDR Pages"
description: "g++, Kompilasi sumber kode C++."
categories: "common"
---
> Bagian dari GCC (GNU Compiler Collection).

> Informasi lebih lanjut: <https://gcc.gnu.org>.

- Mengubah berkas sumber kode menjadi program:

```bash
g++ jalan/menuju/sumber.cpp -o jalan/menuju/program
```

- Menampilkan (hampir) semua kesalahan dan peringatan:

```bash
g++ jalan/menuju/sumber.cpp -Wall -o jalan/menuju/program
```

- Memilih standar bahasa untuk dikompilasi (C++98/C++11/C++14/C++17):

```bash
g++ jalan/menuju/sumber.cpp -std=standar_bahasa -o jalan/menuju/program
```

- Menyertakan pustaka di direktori yang berbeda:

```bash
g++ jalan/menuju/sumber.cpp -o jalan/menuju/program -Ijalur_header -Ljalur_pustaka -lnama_pustaka
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Zein Haddad](mailto:zeinhaddad02@gmail.com) | gcc, g++: add Indonesian translation (#7808) | 2022-02-26T13:04:31 | [50b176125838](https://github.com/tldr-pages/tldr/commit/50b176125838055f5862216fb1bb3fe11cdf3e11)


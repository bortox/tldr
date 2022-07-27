---
author: ['Theodorus Clarence']
date: 1633285867
title: "shuf, TLDR Pages"
description: "shuf, Generate permutasi acak."
categories: "osx"
---
> Informasi lebih lanjut: <https://www.gnu.org/software/coreutils/shuf>.

- Acak urutan baris di sebuah file dan outputkan hasilnya:

```bash
shuf nama_file
```

- Hanya mengoutputkan 5 entri dari hasil:

```bash
shuf -n 5 nama_file
```

- Menuliskan output ke file lain:

```bash
shuf nama_file -o nama_file_output
```

- Men-generate angka acak dari 1-10:

```bash
shuf -i 1-10
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Theodorus Clarence](mailto:55318172+theodorusclarence@users.noreply.github.com) | shuf: add Indonesian translation (#6669) | 2021-10-03T20:31:07 | [30d798659526](https://github.com/tldr-pages/tldr/commit/30d7986595260bc4bf2ef3450a3cde9484a5c66b)


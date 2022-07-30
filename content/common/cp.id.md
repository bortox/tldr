---
author: ['Mulia Nasution', 'Dario Vladović', 'Dewa Widyakumara', 'marchersimon']
date: 1617292466
title: "cp"
description: "cp, Membuat salinan file dan direktori."
categories: "common"
---
> Informasi lebih lanjut: <https://www.gnu.org/software/coreutils/cp>.

- Membuat salinan file ke lokasi lain:

```bash
cp jalan/menuju/file_sumber.ext jalan/menuju/file_tujuan.ext
```

- Menyalin file ke direktori lain, dengan nama yang sama:

```bash
cp jalan/menuju/file_sumber.ext jalan/menuju/direktori_tujuan
```

- Menyalin sebuah direktori secara beserta isinya ke lokasi lain (jika tujuan sudah ada, direktori tersebut disalin ke dalamnya):

```bash
cp -R jalan/menuju/direktori_sumber jalan/menuju/direktori_tujuan
```

- Menyalin sebuah direktori secara beserta isinya, dalam mode `verbose` (menampilkan file-file ketika disalin):

```bash
cp -vR jalan/menuju/direktori_sumber jalan/menuju/direktori_tujuan
```

- Menyalin file-file teks ke lokasi lain, dalam mode interaktif (menampilkan pertanyaan sebelum menimpa):

```bash
cp -i *.txt jalan/menuju/direktori_tujuan
```

- Melepaskan tautan simbolis sebelum menyalin:

```bash
cp -L tautan jalan/menuju/direktori_tujuan
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cp: add more information link (#5556) | 2021-03-30T12:30:03 | [ad46ebe87a57](https://github.com/tldr-pages/tldr/commit/ad46ebe87a578bcb5e61d26addcf1bdfe287d75f)
[Mulia Nasution](mailto:mul14@users.noreply.github.com) | multiple pages: fix lint for Indonesian language (#4847) | 2020-10-28T18:52:26 | [0958fec5db01](https://github.com/tldr-pages/tldr/commit/0958fec5db019bc4550eb34c5616f0175c100763)
[Dewa Widyakumara](mailto:widyakumara@users.noreply.github.com) | alias, cp, mkdir, mv, touch: add Indonesian translation (#4697) | 2020-10-19T17:58:29 | [63bd53ed59ca](https://github.com/tldr-pages/tldr/commit/63bd53ed59cac2bfe8bc5094821d509a094fe19d)


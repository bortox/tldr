---
author: ['Dewa Widyakumara', 'Dario Vladović', 'Mulia Nasution', 'Alessio']
date: 1617292466
title: "mv, TLDR Pages"
description: "mv, Memindah atau menamai-ulang file dan direktori."
categories: "common"
---
> Informasi lebih lanjut: <https://www.gnu.org/software/coreutils/mv>.

- Memindahkan file ke lokasi yang baru:

```bash
mv sumber tujuan
```

- Memindah tanpa meminta konfirmasi sebelum menimpa file yang sudah ada:

```bash
mv -f sumber tujuan
```

- Meminta konfirmasi sebelum menimpa file yang sudah ada, apapun *file permissions*-nya:

```bash
mv -i sumber tujuan
```

- Jangan menimpa file yang sudah ada di direktori tujuan:

```bash
mv -n sumber tujuan
```

- Memindahkan file dalam mode *verbose*, menampilkan file-file yang dipindahkan:

```bash
mv -v sumber tujuan
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[Alessio](mailto:25589202+tomadojuice@users.noreply.github.com) | mv: add more information link (#5542) | 2021-03-29T20:24:45 | [45ff3b27a290](https://github.com/tldr-pages/tldr/commit/45ff3b27a290a760ee43340226e4e85e2091dbfc)
[Mulia Nasution](mailto:mul14@users.noreply.github.com) | multiple pages: fix lint for Indonesian language (#4847) | 2020-10-28T18:52:26 | [0958fec5db01](https://github.com/tldr-pages/tldr/commit/0958fec5db019bc4550eb34c5616f0175c100763)
[Dewa Widyakumara](mailto:widyakumara@users.noreply.github.com) | alias, cp, mkdir, mv, touch: add Indonesian translation (#4697) | 2020-10-19T17:58:29 | [63bd53ed59ca](https://github.com/tldr-pages/tldr/commit/63bd53ed59cac2bfe8bc5094821d509a094fe19d)


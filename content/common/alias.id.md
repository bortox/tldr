---
author: ['Mulia Nasution', 'bl-ue', 'Dewa Widyakumara']
date: 1617130649
title: "alias"
description: "alias, Membuat alias -- kata-kata yang digantikan oleh utasan perintah (command)."
categories: "common"
---
> Alias menjadi kadaluarsa sampai sesi shell saat ini berakhir, kecuali jika didefinisikan di file konfigurasi shell, misalnya `~/.bashrc`.

> Informasi lebih lanjut: <https://tldp.org/LDP/abs/html/aliases.html>.

- Menampilkan daftar semua alias:

```bash
alias
```

- Membuat alias generik:

```bash
alias kata="perintah"
```

- Melihat perintah yang dirujuk oleh alias yang diberikan:

```bash
alias kata
```

- Menghapus alias dari sebuah perintah:

```bash
unalias kata
```

- Mengubah `rm` menjadi perintah interaktif:

```bash
alias rm="rm -i"
```

- Membuat `la` menjadi pintasan untuk `ls -a`:

```bash
alias la="ls -a"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | alias: add more information link (#5644) | 2021-03-30T20:57:29 | [edd9c5a5dc32](https://github.com/tldr-pages/tldr/commit/edd9c5a5dc32839ecf45b50d02d0260b8032002e)
[Mulia Nasution](mailto:mul14@users.noreply.github.com) | multiple pages: fix lint for Indonesian language (#4847) | 2020-10-28T18:52:26 | [0958fec5db01](https://github.com/tldr-pages/tldr/commit/0958fec5db019bc4550eb34c5616f0175c100763)
[Dewa Widyakumara](mailto:widyakumara@users.noreply.github.com) | alias, cp, mkdir, mv, touch: add Indonesian translation (#4697) | 2020-10-19T17:58:29 | [63bd53ed59ca](https://github.com/tldr-pages/tldr/commit/63bd53ed59cac2bfe8bc5094821d509a094fe19d)


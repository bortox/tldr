---
author: ['Reinhart Previano Koentjoro']
date: 1622344356
title: "chkdsk"
description: "chkdsk, Memeriksa dan mencari kesalahan dalam sebuah sistem file dan metadata volume penyimpanan."
categories: "windows"
---
> Informasi lebih lanjut: <https://docs.microsoft.com/windows-server/administration/windows-commands/chkdsk>.

- Memeriksa sebuah ruang penyimpanan berdasarkan huruf drive (diakhiri dengan titik dua), lokasi pemasangan, atau nama ruang:

```bash
chkdsk ruang_penyimpanan
```

- Memperbaiki kesalahan pada ruang penyimpanan yang ditentukan:

```bash
chkdsk ruang_penyimpanan /f
```

- Melepas ruang penyimpanan tertentu untuk pemeriksaan:

```bash
chkdsk ruang_penyimpanan /x
```

- Mengubah ukuran file log dalam sebuah ruang penyimpanan dengan sistem file NTFS:

```bash
chkdsk /lukuran
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | chkdsk: add Indonesian translation (#6067) | 2021-05-30T05:12:36 | [3f425e5b4365](https://github.com/tldr-pages/tldr/commit/3f425e5b436531e54a3ead731f835119a555e8ac)


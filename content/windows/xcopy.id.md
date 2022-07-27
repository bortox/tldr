---
author: ['Reinhart Previano Koentjoro']
date: 1630516880
title: "xcopy, TLDR Pages"
description: "xcopy, Membuat salinan file dan direktori."
categories: "windows"
---
> Informasi lebih lanjut: <https://docs.microsoft.com/windows-server/administration/windows-commands/xcopy>.

- Membuat salinan file atau direktori ke lokasi lain:

```bash
xcopy jalan/menuju/file_atau_direktori_sumber jalan/menuju/file_atau_direktori_tujuan
```

- Melihat daftar file yang akan disalin sebelum proses salinan dimulai:

```bash
xcopy jalan/menuju/file_atau_direktori_sumber jalan/menuju/file_atau_direktori_tujuan /p
```

- Membuat salinan struktur direktori saja (tanpa file di dalamnya):

```bash
xcopy jalan/menuju/file_atau_direktori_sumber jalan/menuju/file_atau_direktori_tujuan /t
```

- Membuat salinan direktori termasuk direktori-direktori kosong (tanpa file):

```bash
xcopy jalan/menuju/file_atau_direktori_sumber jalan/menuju/file_atau_direktori_tujuan /e
```

- Membuat salinan file atau direktori dengan daftar hak akses pengguna (ACL) yang sama:

```bash
xcopy jalan/menuju/file_atau_direktori_sumber jalan/menuju/file_atau_direktori_tujuan /o
```

- Mempersilakan proses penyalinan file atau direktori saat koneksi jaringan komputer terputus:

```bash
xcopy jalan/menuju/file_atau_direktori_sumber jalan/menuju/file_atau_direktori_tujuan /z
```

- Mempersilakan `xcopy` untuk tetap mengganti file yang sudah ada di lokasi tujuan dengan file yang berada di lokasi sumber:

```bash
xcopy jalan/menuju/file_atau_direktori_sumber jalan/menuju/file_atau_direktori_tujuan /y
```

- Menampilkan cara penggunaan secara lengkap:

```bash
xcopy /?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | xcopy: add Indonesian translation (#6449) | 2021-09-01T19:21:20 | [f07d7f6ac530](https://github.com/tldr-pages/tldr/commit/f07d7f6ac530e919cc8b17b27d47f03156a71a75)


---
author: ['Reinhart Previano Koentjoro']
date: 1622303508
title: "find"
description: "find, Mencari teks tertentu di dalam suatu file atau direktori."
categories: "windows"
---
> Informasi lebih lanjut: <https://docs.microsoft.com/windows-server/administration/windows-commands/find>.

- Mencari baris-baris dalam file yang mengandung teks tertentu:

```bash
find teks jalan/menuju/file_atau_direktori
```

- Menunjukkan baris-baris dalam file yang tidak mengandung teks tertentu:

```bash
find teks jalan/menuju/file_atau_direktori /v
```

- Menghitung jumlah baris dalam file yang mengandung teks tertentu:

```bash
find teks jalan/menuju/file_atau_direktori /c
```

- Mencari baris-baris dalam file yang mengandung teks tertentu beserta nomor barisnya:

```bash
find teks jalan/menuju/file_atau_direktori /n
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | find: add Indonesian translation (#6066) | 2021-05-29T17:51:48 | [3f473b43d70d](https://github.com/tldr-pages/tldr/commit/3f473b43d70d2f6b7bd12c194b28227b20f37de4)


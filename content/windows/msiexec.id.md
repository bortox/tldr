---
author: ['Reinhart Previano Koentjoro']
date: 1640861829
title: "msiexec, TLDR Pages"
description: "msiexec, Memasang, memperbarui, memperbaiki, atau menghapus program Windows melalui file MSI dan MSP yang tersedia."
categories: "windows"
---
> Informasi lebih lanjut: <https://docs.microsoft.com/windows-server/administration/windows-commands/msiexec>.

- Memasang sebuah program melalui file MSI:

```bash
msiexec /package jalan/menuju/file.msi
```

- Memasang file MSI dari internet:

```bash
msiexec /package https://example.com/installer.msi
```

- Memasang pembaruan program melalui file MSP:

```bash
msiexec /update jalan/menuju/file.msp
```

- Menghapus pemasangan atau pembaruan program melalui file MSI atau MSP yang tersedia:

```bash
msiexec /uninstall jalan/menuju/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | msiexec: add Indonesian translation (#7537) | 2021-12-30T11:57:09 | [491f0fcefb09](https://github.com/tldr-pages/tldr/commit/491f0fcefb096c9de04b5c614c0c173ae5befaff)


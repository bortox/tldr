---
author: ['Reinhart Previano Koentjoro']
date: 1629959966
title: "getprop, TLDR Pages"
description: "getprop, Menampilkan informasi terhadap properti sistem operasi Android."
categories: "android"
---
> Informasi lebih lanjut: <https://manned.org/getprop>.

- Menampilkan informasi daftar properti sistem operasi Android:

```bash
getprop
```

- Menampilan informasi terhadap properti sistem tertentu:

```bash
getprop properti
```

- Menampilkan tingkat API SDK Android:

```bash
getprop ro.build.version.sdk
```

- Menampilkan versi sistem operasi Android:

```bash
getprop ro.build.version.release
```

- Menampilkan kode model perangkat Android:

```bash
getprop ro.vendor.product.model
```

- Menampilkan status pembukaan kunci pembuat perangkat (OEM):

```bash
getprop ro.oem_unlock_supported
```

- Menampilkan alamat MAC terhadap komponen Wi-Fi milik perangkat:

```bash
getprop ro.boot.wifimacaddr
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | android/*: add Indonesian translation (#6399) | 2021-08-26T08:39:26 | [2ff6d3a89fd7](https://github.com/tldr-pages/tldr/commit/2ff6d3a89fd70c776e9fdebef1708fa7ff76e2cd)


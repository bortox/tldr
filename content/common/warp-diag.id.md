---
author: ['Reinhart Previano Koentjoro']
date: 1635359616
title: "warp-diag"
description: "warp-diag, Alat diagnostik dan umpan balik bagi layanan Cloudflare WARP."
categories: "common"
---
> Lihat juga: `warp-cli`.

> Informasi lebih lanjut: <https://developers.cloudflare.com/warp-client/>.

- Membuat sebuah file arsip (zip) berisi informasi konfigurasi sistem dan log debug terhadap koneksi WARP:

```bash
warp-diag
```

- Membuat sebuah file arsip diagnostik dengan membubuhkan stempel waktu ke dalam nama file:

```bash
warp-diag --add-ts
```

- Menyimpan file arsip diagnostik ke dalam direktori tertentu:

```bash
warp-diag --output jalan/menuju/direktori
```

- Memberikan saran kepada Cloudflare WARP secara interaktif:

```bash
warp-diag feedback
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | warp-cli, warp-diag: add Indonesian translation (#7192) | 2021-10-27T20:33:36 | [fefc34e5d45a](https://github.com/tldr-pages/tldr/commit/fefc34e5d45a0feaa9464381540d4ffe1189605c)


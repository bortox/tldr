---
author: ['Theodorus Clarence']
date: 1633516141
title: "gh, TLDR Pages"
description: "gh, Memudahkan pengaksesan GitHub dari command-line."
categories: "common"
---
> Beberapa subcommands seperti `gh config` memiliki dokumentasi sendiri.

> Informasi lebih lanjut: <https://cli.github.com/>.

- Mengklon sebuah GitHub repositori di lokal

```bash
gh repo clone pemilik/repositori
```

- Membuat isu baru:

```bash
gh issue create
```

- Melihat dan filter issue yang sedang open pada repositori:

```bash
gh issue list
```

- Melihat isu di browser:

```bash
gh issue view --web nomor_isu
```

- Membuat sebuah pull request:

```bash
gh pr create
```

- Melihat pull request di browser:

```bash
gh pr view --web nomor_pr
```

- Mengecek pada local branch sebuah pull request, diikuti dengan nomor pull requestnya:

```bash
gh pr checkout nomor_pr
```

- Mengecek status pull request pada sebuah repository:

```bash
gh pr status
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Theodorus Clarence](mailto:55318172+theodorusclarence@users.noreply.github.com) | gh: add Indonesian translation (#6670) | 2021-10-06T12:29:01 | [627ae71aed4c](https://github.com/tldr-pages/tldr/commit/627ae71aed4c22f69cca8e3a234b69aa67163435)


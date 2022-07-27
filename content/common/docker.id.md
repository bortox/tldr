---
author: ['Irham Dzuhri', 'bl-ue', 'marchersimon']
date: 1631521281
title: "docker, TLDR Pages"
description: "docker, Mengatur kontainer Docker dan image."
categories: "common"
---
> Kami mempunyai dokumentasi terpisah untuk menggunakan subperintah seperti `docker run`.

> Informasi lebih lanjut: <https://docs.docker.com/engine/reference/commandline/cli/>.

- Menampilkan semua daftar kontainer docker yang sedang berjalan:

```bash
docker ps
```

- Menampilkan semua daftar kontainer docker (yang sedang berjalan dan berhenti):

```bash
docker ps -a
```

- Memulai sebuah kontainer dari image, dengan nama kustom:

```bash
docker run --name nama_kontainer image
```

- Memulai atau menghentikan kontainer yang tersedia:

```bash
docker start|stop nama_kontainer
```

- Menarik image dari registri docker:

```bash
docker pull image
```

- Membuka shell didalam sebuah kontainer yang sedang berjalan:

```bash
docker exec -it nama_kontainer sh
```

- Menghapus kontainer yang sedang berhenti:

```bash
docker rm nama_kontainer
```

- Mengambil dan mengikuti semua log dari sebuah kontainer:

```bash
docker logs -f nama_kontainer
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Irham Dzuhri](mailto:irhamdz@gmail.com) | curl, docker, git, git-add, git-commit, git-status, npm: add Indonesian translation (#4602) | 2020-10-12T23:51:19 | [9f52c5371c1b](https://github.com/tldr-pages/tldr/commit/9f52c5371c1baeffc86b9dd2f651ebedb493700b)


---
author: ['JoeStone13']
date: 1635603519
title: "ab, TLDR Pages"
description: "ab, Apache HTTP server referansemåling verktøy."
categories: "common"
---
> Mer informasjon: <https://httpd.apache.org/docs/current/programs/ab.html>.

- Utfør 100 HTTP GET-forespørsler til en gitt URL:

```bash
ab -n 100 url
```

- Utfør 100 HTTP GET-forespørsler, i samtidige grupper på 10, til en URL:

```bash
ab -n 100 -c 10 url
```

- Utfør 100 HTTP POST-forespørsler til en URL, med å bruke en JSON-nyttelast fra en fil:

```bash
ab -n 100 -T application/json -p vei/til/fil.json url
```

- Bruk HTTP [K]eep Alive, dvs. utfør flere forespørsler i én HTTP-økt:

```bash
ab -k url
```

- Angi maksimalt antall sekunder å bruke på referansemåling:

```bash
ab -t 60 url
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[JoeStone13](mailto:captainjoestone@gmail.com) | ab: add Norwegian translation (#7291) | 2021-10-30T16:18:39 | [f012ea3e5615](https://github.com/tldr-pages/tldr/commit/f012ea3e56156f5e31d0617c6e99ae7b3efe4645)


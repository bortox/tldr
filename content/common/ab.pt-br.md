---
author: ['bl-ue', 'Marco Bonelli']
date: 1615671899
title: "ab"
description: "ab, Ferramenta da Apache para realizar benchmarking e testes de carga em servidores web."
categories: "common"
---
> Mais informações: <https://httpd.apache.org/docs/current/programs/ab.html>.

- Executar 100 requisições HTTP do tipo GET para uma determinada URL:

```bash
ab -n 100 url
```

- Executar 100 requisições HTTP do tipo GET para uma determinada URL, executando 10 requisições simultâneas de cada vez:

```bash
ab -n 100 -c 10 url
```

- Utilizar a funcionalidade HTTP Keep Alive, permitindo que várias requisições sejam feitas em uma sessão HTTP:

```bash
ab -k url
```

- Definir o tempo total do benchmarking, em segundos:

```bash
ab -t 60 url
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | ab: update grammar; update link (#5433) | 2021-03-13T22:44:59 | [8f2ed246f761](https://github.com/tldr-pages/tldr/commit/8f2ed246f7614df6e815b9eefae053a0f64df920)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)


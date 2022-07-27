---
author: ['Marco Bonelli', 'Stig124', 'Anja Elzinger']
date: 1634201302
title: "beep, TLDR Pages"
description: "beep, Utilitário que permite o computador emitir sons."
categories: "linux"
---
> Mais informações: <https://github.com/spkr-beep/beep>.

- Emitir um som:

```bash
beep
```

- Emitir um som repetidamente:

```bash
beep -r repeticoes
```

- Emitir um som em uma frequência (Hz) específica e com duração específica (milisegundos):

```bash
beep -f frequencia -l duracao
```

- Emitir cada frequência e duração como um som diferente:

```bash
beep -f frequencia -l duracao -n -f frequencia -l duracao
```

- Executar a escala de Dó maior:

```bash
beep -f 262 -n -f 294 -n -f 330 -n -f 349 -n -f 392 -n -f 440 -n -f 494 -n -f 523
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Anja Elzinger](mailto:35960947+entensee403@users.noreply.github.com) | beep: add German translation (#6939) | 2021-10-14T10:48:22 | [6c5fe7692586](https://github.com/tldr-pages/tldr/commit/6c5fe7692586c9913e3b490efffc5011764ccadc)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)


---
author: ['Carlo Federico Vescovo', 'Lucas Gabriel Schneider', 'Kyle', 'Matthias Lübken']
date: 1629747204
title: "base64, TLDR Pages"
description: "base64, Codifica e decodifica utilizzando la rappresentazione in base64."
categories: "osx"
---
> Maggiori informazioni: <https://www.unix.com/man-page/osx/1/base64/>.

- Codifica un file:

```bash
base64 -i file_da_codificare
```

- Decodifica un file:

```bash
base64 --decode -i file_da_decodificare
```

- Codifica da stdin:

```bash
echo -n testo_da_codificare | base64
```

- Decodifica da stdin:

```bash
echo -n testo_da_decodificare | base64 --decode
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Matthias Lübken](mailto:matthias.luebken@gmail.com) | base32, base64: fix -D flag (#5234) | 2021-03-07T23:58:11 | [00e00396a42a](https://github.com/tldr-pages/tldr/commit/00e00396a42a8b5fcc189909a1aae3173e513f72)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Carlo Federico Vescovo](mailto:vescovocarlofederico@gmail.com) | asr, base64, caffeinate, diskutil: add Italian translation (#4451) | 2020-10-05T16:32:45 | [a0d7ca3f3e7e](https://github.com/tldr-pages/tldr/commit/a0d7ca3f3e7e678c8c388b6158c3225eca27fee1)


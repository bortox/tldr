---
author: ['Waldir Pimenta', 'Kyle', 'Emily Grace Seville', 'Jakub Beneš', 'andyxning', '7anshuai', 'Matthias Lübken', 'andrazznidar', 'Lucas Gabriel Schneider']
date: 1644837703
title: "base64, TLDR Pages"
description: "base64, Encode and decode using Base64 representation."
categories: "osx"
---
> More information: <https://www.unix.com/man-page/osx/1/base64/>.

- Encode a file:

```bash
base64 --input=plain_file
```

- Decode a file:

```bash
base64 --decode --input=base64_file
```

- Encode from stdin:

```bash
echo -n "plain_text" | base64
```

- Decode from stdin:

```bash
echo -n base64_text | base64 --decode
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Matthias Lübken](mailto:matthias.luebken@gmail.com) | base32, base64: fix -D flag (#5234) | 2021-03-07T23:58:11 | [00e00396a42a](https://github.com/tldr-pages/tldr/commit/00e00396a42a8b5fcc189909a1aae3173e513f72)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[andrazznidar](mailto:andrazznidar@users.noreply.github.com) | Incorrect entry for "Decode a file" (#2117) | 2018-05-21T23:20:53 | [c2a807613421](https://github.com/tldr-pages/tldr/commit/c2a807613421c04c71aedee77bd9d6f693f4f14c)
[Jakub Beneš](mailto:jukben@gmail.com) | base64: lowercase -d example (#2079) | 2018-04-21T13:22:44 | [7d693c4da030](https://github.com/tldr-pages/tldr/commit/7d693c4da030a768bcd67d2439bd1d3210d00c76)
[7anshuai](mailto:7anshuai@gmail.com) | base64: add the -n option of echo in examples | 2017-12-28T11:16:18 | [3b8036fbc202](https://github.com/tldr-pages/tldr/commit/3b8036fbc2026ce5580675cd9947f43da7eec03c)
[andyxning](mailto:andy.xning@gmail.com) | add base64 for osx | 2016-01-18T12:40:48 | [398a93be5210](https://github.com/tldr-pages/tldr/commit/398a93be52107f86bff66c7fccb651d81b5d1c8c)


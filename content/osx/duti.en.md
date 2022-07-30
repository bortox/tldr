---
author: ['Kyle', 'Lucas Gabriel Schneider', 'Emily Grace Seville', 'Darryl Abbate']
date: 1644837703
title: "duti"
description: "duti, Set default applications for document types and URL schemes on macOS."
categories: "osx"
---
> More information: <https://github.com/moretension/duti>.

- Set Safari as the default handler for HTML documents:

```bash
duti -s com.apple.Safari public.html all
```

- Set VLC as the default viewer for files with `.m4v` extensions:

```bash
duti -s org.videolan.vlc m4v viewer
```

- Set Finder as the default handler for the ftp:// URL scheme:

```bash
duti -s com.apple.Finder "ftp"
```

- Display information about the default application for a given extension:

```bash
duti -x ext
```

- Display the default handler for a given UTI:

```bash
duti -d uti
```

- Display all handlers of a given UTI:

```bash
duti -l uti
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Darryl Abbate](mailto:rootbeersoup@gmail.com) | duti: add page (#2287) | 2018-09-03T20:04:38 | [7fca2dcc0700](https://github.com/tldr-pages/tldr/commit/7fca2dcc0700a08001c64c6c0257a184b59b87f4)


---
author: ['marcan2020', 'bl-ue', 'Ultimate Pea', 'Seth Falco']
date: 1634181756
title: "identify"
description: "identify, Command-line utility of Image Magick project to describe the format and characteristics of one or more image files."
categories: "common"
---
> More information: <https://imagemagick.org/script/identify.php>.

- Describe the format and basic characteristics of an image:

```bash
identify path/to/image
```

- Describe the format and verbose characteristics of an image:

```bash
identify -verbose path/to/image
```

- Collect dimensions of all JPEG files under current directory:

```bash
identify -format "%f,%w,%h\n" *.jpg > path/to/filelist.csv
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marcan2020](mailto:marcan2020@gmail.com) | identify: add 2 examples (#6684) | 2021-10-14T05:22:36 | [afc5e4e55d6a](https://github.com/tldr-pages/tldr/commit/afc5e4e55d6a032b40f6ad2161807683383cd87a)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Ultimate Pea](mailto:superchenzb@gmail.com) | identify: add page (#4036) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> Co-authored-by: Andrik Albuquerque [...] | 2020-05-16T01:12:43 | [070f5ae8d6e2](https://github.com/tldr-pages/tldr/commit/070f5ae8d6e212406800e503dbe0c8e0dab58091)


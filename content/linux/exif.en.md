---
author: ['Lucas Gabriel Schneider', 'Andrew Fehr']
date: 1612112718
title: "exif"
description: "exif, Show and change EXIF information in JPEG files."
categories: "linux"
---
> More information: <https://github.com/libexif/exif/>.

- Show all recognized EXIF information in an image:

```bash
exif path/to/image.jpg
```

- Show a table listing known EXIF tags and whether each one exists in an image:

```bash
exif --list-tags --no-fixup image.jpg
```

- Extract the image thumbnail into the file `thumbnail.jpg`:

```bash
exif --extract-thumbnail --output=thumbnail.jpg image.jpg
```

- Show the raw contents of the "Model" tag in the given image:

```bash
exif --ifd=0 --tag=Model --machine-readable image.jpg
```

- Change the value of the "Artist" tag to John Smith and save to `new.jpg`:

```bash
exif --output=new.jpg --ifd=0 --tag="Artist" --set-value="John Smith" --no-fixup image.jpg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Andrew Fehr](mailto:andrewfehr@outlook.com) | exif: add page (#4670) | 2020-10-15T00:43:43 | [f51a9fa0934a](https://github.com/tldr-pages/tldr/commit/f51a9fa0934a0196aa9d37948d481e1913ca290d)


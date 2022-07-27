---
author: ['marchersimon']
date: 1631084155
title: "feh, TLDR Pages"
description: "feh, Lightweight image viewing utility."
categories: "common"
---
> More information: <https://feh.finalrewind.org>.

- View images locally or using a URL:

```bash
feh path/to/images
```

- View images recursively:

```bash
feh --recursive path/to/images
```

- View images without window borders:

```bash
feh --borderless path/to/images
```

- Exit after the last image:

```bash
feh --cycle-once path/to/images
```

- Set the slideshow cycle delay:

```bash
feh --slideshow-delay seconds path/to/images
```

- Set your wallpaper (centered, filled, maximized, scaled or tiled):

```bash
feh --bg-center|fill|max|scale|tile path/to/image
```

- Create a montage of all images within a directory. Outputs as a new image:

```bash
feh --montage --thumb-height 150 --thumb-width 150 --index-info "%nn%wx%h" --output path/to/montage_image.png
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | feh, hostname, fc, ssh-add: move to common (#6487) | 2021-09-08T08:55:55 | [4ef097c3581a](https://github.com/tldr-pages/tldr/commit/4ef097c3581a5a5d6a740b23629e82852b59680c)


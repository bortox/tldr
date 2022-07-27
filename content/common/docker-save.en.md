---
author: ['Ali Malek', 'Lucas Gabriel Schneider']
date: 1612112718
title: "docker save, TLDR Pages"
description: "docker save, Export one or more docker images to archive."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/save/>.

- Save an image by redirecting stdout to a tar archive:

```bash
docker save image:tag > path/to/file.tar
```

- Save an image to a tar archive:

```bash
docker save --output path/to/file.tar image:tag
```

- Save all tags of the image:

```bash
docker save --output path/to/file.tar image_name
```

- Cherry-pick particular tags of an image to save:

```bash
docker save --output path/to/file.tar image_name:tag1 image_name:tag2 ...
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Ali Malek](mailto:ali.malek.71@gmail.com) | docker-save: add page (#4936) | 2020-11-10T20:38:14 | [13ec447aaf1a](https://github.com/tldr-pages/tldr/commit/13ec447aaf1ad48b848d382350f6228191c82230)


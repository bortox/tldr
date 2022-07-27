---
author: ['Phil Ewels', 'Seth Falco', 'marchersimon']
date: 1658921926
title: "singularity, TLDR Pages"
description: "singularity, Manage Singularity containers and images."
categories: "common"
---
> More information: <https://singularity-docs.readthedocs.io/en/latest/#commands>.

- Download a remote image from Sylabs Cloud:

```bash
singularity pull --name image.sif library://godlovedc/funny/lolcow:latest
```

- Rebuild a remote image using the latest Singularity image format:

```bash
singularity build image.sif docker://godlovedc/lolcow
```

- Start a container from an image and get a shell inside it:

```bash
singularity shell image.sif
```

- Start a container from an image and run a command:

```bash
singularity exec image.sif command
```

- Start a container from an image and execute the internal runscript:

```bash
singularity run image.sif
```

- Build a singularity image from a recipe file:

```bash
sudo singularity build image.sif recipe
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: add/edit more information link (#8255) | 2022-07-27T13:38:46 | [df1c9855a704](https://github.com/tldr-pages/tldr/commit/df1c9855a704f1360748c4b7652f8bca1db3a6c7)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Phil Ewels](mailto:phil.ewels@scilifelab.se) | singularity: update file formats, replace shub with scloud (#3267) | 2019-09-16T09:35:23 | [ad4c282c7589](https://github.com/tldr-pages/tldr/commit/ad4c282c758955a8f688415e7e3c74baf58e8fc8)
[Phil Ewels](mailto:phil.ewels@scilifelab.se) | singularity: Remove erroneous dash | 2018-01-12T12:49:58 | [14e174aab31e](https://github.com/tldr-pages/tldr/commit/14e174aab31e9b21d9ccf0239771bb1f2e2dcad8)
[Phil Ewels](mailto:phil.ewels@scilifelab.se) | singularity: add page | 2018-01-12T12:43:07 | [6fec9fef957e](https://github.com/tldr-pages/tldr/commit/6fec9fef957e98b4e67e31a87882494d43326720)


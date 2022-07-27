---
author: ['Furkan']
date: 1634756728
title: "in-toto-run, TLDR Pages"
description: "in-toto-run, Generating link metadata while carrying out a supply chain step."
categories: "common"
---
> More information: <https://in-toto.readthedocs.io/en/latest/command-line-tools/in-toto-run.html>.

- Tag a git repo and signing the resulting link file:

```bash
in-toto-run -n tag --products . -k key_file -- git tag v1.0
```

- Create a tarball, storing files as materials and the tarball as product:

```bash
in-toto-run -n package -m project -p project.tar.gz -- tar czf project.tar.gz project
```

- Generate signed attestations for review work:

```bash
in-toto-run -n review -k key_file -m document.pdf -x
```

- Scan the image using Trivy and generate link file:

```bash
in-toto-run -n scan -k key_file -p report.json -- /bin/sh -c "trivy -o report.json -f json <IMAGE>"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Furkan](mailto:furkan.turkal@trendyol.com) | in-toto-run: add page | 2021-10-20T21:05:28 | [cf48eaba7fe8](https://github.com/tldr-pages/tldr/commit/cf48eaba7fe85511ff2ddf87d3fe7f1f27c67740)


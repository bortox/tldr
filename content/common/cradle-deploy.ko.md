---
author: ['bl-ue']
date: 1610858159
title: "cradle deploy"
description: "cradle deploy, Cradle 배포 관리."
categories: "common"
---
> 더 많은 정보: <https://cradlephp.github.io/docs/3.B.-Reference-Command-Line-Tools.html#deploy>.

- 서버에 Cradle을 배포:

```bash
cradle deploy production
```

- 아마존 S3에 정적 자산 배포:

```bash
cradle deploy s3
```

- Yarn "components" 디렉토리를 포함하여 정적 자산 배포:

```bash
cradle deploy s3 --include-yarn
```

- "upload" 디렉토리를 포함한 정적 자산 배포:

```bash
cradle deploy s3 --include-upload
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | cradle-deploy: fix page name | 2021-01-17T05:35:59 | [fefe4075e8b6](https://github.com/tldr-pages/tldr/commit/fefe4075e8b6127cddf7f92684ad2d014d8d0dac)


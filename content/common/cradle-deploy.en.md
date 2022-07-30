---
author: ['Owen Voke', 'pxgamer']
date: 1560099229
title: "cradle deploy"
description: "cradle deploy, Manage Cradle deployments."
categories: "common"
---
> More information: <https://cradlephp.github.io/docs/3.B.-Reference-Command-Line-Tools.html#deploy>.

- Deploy Cradle to a server:

```bash
cradle deploy production
```

- Deploy static assets to Amazon S3:

```bash
cradle deploy s3
```

- Deploy static assets including the Yarn "components" directory:

```bash
cradle deploy s3 --include-yarn
```

- Deploy static assets including the "upload" directory:

```bash
cradle deploy s3 --include-upload
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | cradle-deploy: add link to homepage | 2019-06-09T18:53:49 | [4c3996a26276](https://github.com/tldr-pages/tldr/commit/4c3996a26276c9a0b6f44fb684ab49237e10c81e)
[Owen Voke](mailto:owzie123@gmail.com) | cradle-deploy: add page (#2562) | 2018-11-09T17:28:21 | [26dc3c3498ae](https://github.com/tldr-pages/tldr/commit/26dc3c3498ae772d76cb99be1587edbc731b24a1)


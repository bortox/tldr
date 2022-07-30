---
author: ['cpetrella-sketch']
date: 1639652789
title: "doctl apps"
description: "doctl apps, Used to manage digitalocean apps."
categories: "common"
---
> More information: <https://docs.digitalocean.com/reference/doctl/reference/apps>.

- Create an app:

```bash
doctl apps create
```

- Create a deployment for a specific app:

```bash
doctl apps create-deployment app_id
```

- Delete an app interactively:

```bash
doctl apps delete app_id
```

- Get an app:

```bash
doctl apps get
```

- List all apps:

```bash
doctl apps list
```

- List all deployments from a specific app:

```bash
doctl apps list-deployments app_id
```

- Get logs from a specific app:

```bash
doctl apps logs app_id
```

- Update a specific app with a given app spec:

```bash
doctl apps update app_id --spec path/to/spec.yml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[cpetrella-sketch](mailto:78937129+cpetrella-sketch@users.noreply.github.com) | doctl-apps: add page (#7501) | 2021-12-16T12:06:29 | [aa4932c7a824](https://github.com/tldr-pages/tldr/commit/aa4932c7a824e7129111e094f5ba406d321903a9)


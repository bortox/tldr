---
author: ['bl-ue', 'stets']
date: 1610197216
title: "valet"
description: "valet, A Laravel development environment that allows hosting sites via local tunnels on `http://<example>.test`."
categories: "osx"
---
> More information: <https://laravel.com/docs/8.x/valet>.

- Start the valet daemon:

```bash
valet start
```

- Register the current working directory as a path that Valet should search for sites:

```bash
valet park
```

- View 'parked' paths:

```bash
valet paths
```

- Serve a single site instead of an entire directory:

```bash
valet link app-name
```

- Share a project via an Ngrok tunnel:

```bash
valet share
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | valet: update more information link (#5121) | 2021-01-09T14:00:16 | [feb804162ba0](https://github.com/tldr-pages/tldr/commit/feb804162ba06055a22e8a788b284b835d69bef1)
[stets](mailto:stetsblake@gmail.com) | valet: add page (#3266) | 2019-09-20T17:56:59 | [ce995955d4ce](https://github.com/tldr-pages/tldr/commit/ce995955d4ce73ef99354a129e3db66b87679b3d)


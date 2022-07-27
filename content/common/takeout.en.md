---
author: ['Owen Voke']
date: 1610627523
title: "takeout, TLDR Pages"
description: "takeout, A Docker-based development-only dependency manager."
categories: "common"
---
> More information: <https://github.com/tighten/takeout>.

- Display a list of available services:

```bash
takeout enable
```

- Enable a specific service:

```bash
takeout enable name
```

- Enable a specific service with the default parameters:

```bash
takeout enable --default name
```

- Display a list of enabled services:

```bash
takeout disable
```

- Disable a specific service:

```bash
takeout disable name
```

- Disable all services:

```bash
takeout disable --all
```

- Start a specific container:

```bash
takeout start container_id
```

- Stop a specific container:

```bash
takeout stop container_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | takeout: add page (#5138) | 2021-01-14T13:32:03 | [357914393db3](https://github.com/tldr-pages/tldr/commit/357914393db3489cc092e15c210c1f293e88f29e)


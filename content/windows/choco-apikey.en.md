---
author: ['Owen Voke', 'Marco Bonelli']
date: 1559564381
title: "choco-apikey"
description: "choco-apikey, Manage API keys for Chocolatey sources."
categories: "windows"
---
> More information: <https://chocolatey.org/docs/commands-apikey>.

- Display a list of sources and their API keys:

```bash
choco apikey
```

- Display a specific source and its API key:

```bash
choco apikey --source "source_url"
```

- Set an API key for a source:

```bash
choco apikey --source "source_url" --key "api_key"
```

- Remove an API key for a source:

```bash
choco apikey --source "source_url" --remove
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | choco-apikey: add page (#2836) | 2019-04-01T19:38:51 | [c015b89e85c1](https://github.com/tldr-pages/tldr/commit/c015b89e85c19a4c26c33cb98afea2f7a7c5aeaf)


---
author: ['pxgamer', 'Starbeamrainbowlabs']
date: 1559676580
title: "minetestserver"
description: "minetestserver, Multiplayer infinite-world block sandbox server."
categories: "common"
---
> See also `minetest`, the graphical client.

> More information: <https://wiki.minetest.net/Setting_up_a_server>.

- Start the server:

```bash
minetestserver
```

- List available worlds:

```bash
minetestserver --world list
```

- Specify the world name to load:

```bash
minetestserver --world world_name
```

- List the available game IDs:

```bash
minetestserver --gameid list
```

- Specify a game to use:

```bash
minetestserver --gameid game_id
```

- Listen on a specific port:

```bash
minetestserver --port 34567
```

- Migrate to a different data backend:

```bash
minetestserver --migrate sqlite3|leveldb|redis
```

- Start an interactive terminal after starting the server:

```bash
minetestserver --terminal
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | minetestserver: add link to homepage | 2019-06-04T21:29:40 | [1139d582c0d3](https://github.com/tldr-pages/tldr/commit/1139d582c0d3817f1bfbcdbc7bfcd30eb21de337)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | minetestserver: add page (#2463) | 2018-10-20T13:20:42 | [285e84f418ae](https://github.com/tldr-pages/tldr/commit/285e84f418ae76868a79bd6e843be694ce3174a5)


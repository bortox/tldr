---
author: ['Ben Allen', 'Peter Babič']
date: 1620994268
title: "uuidgen"
description: "uuidgen, Generate unique identifiers (UUIDs)."
categories: "linux"
---
> See also `uuid`.

> More information: <https://manned.org/uuidgen>.

- Create a random UUIDv4:

```bash
uuidgen --random
```

- Create a UUIDv1 based on the current time:

```bash
uuidgen --time
```

- Create a UUIDv5 of the name with a specified namespace prefix:

```bash
uuidgen --sha1 --namespace @dns|@url|@oid|@x500 --name object_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Peter Babič](mailto:peter@babic.dev) | uuid: add page, uuidgen: update description (#5892) | 2021-05-14T14:11:08 | [f67ba5ca5061](https://github.com/tldr-pages/tldr/commit/f67ba5ca5061e5ee1b9a3e1617d6a51a81e0c189)
[Ben Allen](mailto:ben.allen@gmail.com) | uuidgen: add page | 2018-12-22T17:27:25 | [75bc70055778](https://github.com/tldr-pages/tldr/commit/75bc7005577896bbbd57178abc4f8423a38998ef)


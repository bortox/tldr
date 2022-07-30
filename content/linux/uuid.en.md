---
author: ['Peter Babič']
date: 1620994268
title: "uuid"
description: "uuid, Generate and decode Universally Unique Identifiers (UUID)."
categories: "linux"
---
> See also `uuidgen`.

> More information: <https://manned.org/uuid>.

- Generate a UUIDv1 (based on time and system's hardware address, if present):

```bash
uuid
```

- Generate a UUIDv4 (based on random data):

```bash
uuid -v 4
```

- Generate multiple UUIDv4 identifiers at once:

```bash
uuid -v 4 -n number_of_uuids
```

- Generate a UUIDv4 and specify the output format:

```bash
uuid -v 4 -F BIN|STR|SIV
```

- Generate a UUIDv4 and write the output to a file:

```bash
uuid -v 4 -o path/to/file
```

- Generate a UUIDv5 (based on the supplied object name) with a specified namespace prefix:

```bash
uuid -v 5 ns:DNS|URL|OID|X500 object_name
```

- Decode a given UUID:

```bash
uuid -d uuid
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Peter Babič](mailto:peter@babic.dev) | uuid: add page, uuidgen: update description (#5892) | 2021-05-14T14:11:08 | [f67ba5ca5061](https://github.com/tldr-pages/tldr/commit/f67ba5ca5061e5ee1b9a3e1617d6a51a81e0c189)


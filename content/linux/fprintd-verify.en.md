---
author: ['Axel Navarro']
date: 1636070659
title: "fprintd-verify"
description: "fprintd-verify, Verify fingerprints against the database."
categories: "linux"
---
> More information: <https://manned.org/fprintd-verify>.

- Verify all stored fingerprints for the current user:

```bash
fprintd-verify
```

- Verify a specific fingerprint for the current user:

```bash
fprintd-verify --finger left-thumb|left-index-finger|left-middle-finger|left-ring-finger|left-little-finger|right-thumb|right-index-finger|right-middle-finger|right-ring-finger|right-little-finger
```

- Verify fingerprints for a specific user:

```bash
fprint-verify username
```

- Verify a specific fingerprint for a specific user:

```bash
fprintd-verify --finger finger_name username
```

- Fail the process if a fingerprint doesn't match with ones stored in the database for the current user:

```bash
fprint-verify --g-fatal-warnings
```

- Display help:

```bash
fprintd-verify --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | fprintd-verify: add page (#7178) | 2021-11-05T01:04:19 | [d0c13382a81b](https://github.com/tldr-pages/tldr/commit/d0c13382a81b517ccb6dd766176081c39ef302dd)


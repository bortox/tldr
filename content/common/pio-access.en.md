---
author: ['marchersimon']
date: 1616956111
title: "pio access"
description: "pio access, Set the access level on published resources (packages) in the registry."
categories: "common"
---
> More information: <https://docs.platformio.org/en/latest/core/userguide/access/>.

- Grant a user access to a resource:

```bash
pio access grant guest|maintainer|admin username resource_urn
```

- Remove a user's access to a resource:

```bash
pio access revoke username resource_urn
```

- Show all resources that a user or team has access to and the access level:

```bash
pio access list username
```

- Restrict access to a resource to specific users or team members:

```bash
pio access private resource_urn
```

- Allow all users access to a resource:

```bash
pio access public resource_urn
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pio-access: add page (#5518) | 2021-03-28T20:28:31 | [5460bb9b94fe](https://github.com/tldr-pages/tldr/commit/5460bb9b94feea4cfb52ef85e978c42abd41b247)


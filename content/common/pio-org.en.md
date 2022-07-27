---
author: ['marchersimon']
date: 1617101154
title: "pio org, TLDR Pages"
description: "pio org, Manage PlatformIO organizations and their owners."
categories: "common"
---
> More information: <https://docs.platformio.org/en/latest/core/userguide/org/>.

- Create a new organization:

```bash
pio org create organization_name
```

- Delete an organization:

```bash
pio org destroy organization_name
```

- Add a user to an organization:

```bash
pio org add organization_name username
```

- Remove a user from an organization:

```bash
pio org remove organization_name username
```

- List all organizations the current user is a member of and their owners:

```bash
pio org list
```

- Update the name, email or display name of an organization:

```bash
pio org update --orgname new_organization_name --email new_email --displayname new_display_name organization_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pio-org: add page (#5525) | 2021-03-30T12:45:54 | [da099ba8115a](https://github.com/tldr-pages/tldr/commit/da099ba8115a094f6f2db6ab49154fdc97144568)


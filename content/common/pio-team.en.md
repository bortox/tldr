---
author: ['marchersimon']
date: 1617200812
title: "pio team, TLDR Pages"
description: "pio team, Manage PlatformIO teams."
categories: "common"
---
> More information: <https://docs.platformio.org/en/latest/core/userguide/team/>.

- Create a new team with the specified description:

```bash
pio team create --description description organization_name:team_name
```

- Delete a team:

```bash
pio team destroy organization_name:team_name
```

- Add a new user to a team:

```bash
pio team add organization_name:team_name username
```

- Remove a user from a team:

```bash
pio team remove organization_name:team_name username
```

- List all teams that the user is part of and their members:

```bash
pio team list
```

- List all teams in an organization:

```bash
pio team list organization_name
```

- Rename a team:

```bash
pio team update --name new_team_name organization_name:team_name
```

- Change the description of a team:

```bash
pio team update --description new_description organization_name:team_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pio-team: add page (#5524) | 2021-03-31T16:26:52 | [e00c94e3bb6e](https://github.com/tldr-pages/tldr/commit/e00c94e3bb6e14918d12897c33db543c0eb1a50c)

